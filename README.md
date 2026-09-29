# Cheeko Video Library

The public page for every Cheeko marketing video: thumbnail, what it's about, a Watch button and the ready-to-copy caption, in English and Hindi.

Live page: https://craftech360-projects.github.io/cheeko-video-library/

Videos play from the "Public videos" folder in Google Drive, the only public part of the Cheeko videos Drive. Nothing else is linked from this page.

## Updating

This page is generated. Don't edit `index.html` by hand. After new videos are published to Drive (`marketing/tools/publish_to_drive.py`), run `marketing/tools/deploy_library.sh`. It rebuilds the page with `library_page.py --site` and pushes it here; GitHub Pages serves it within a minute or two.

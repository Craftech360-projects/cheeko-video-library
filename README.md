# Cheeko Video Library

The team's page for every Cheeko marketing video: thumbnail, what it's about, and links to watch it, the Ready to post files, all files and the script, plus the caption for English and Hindi.

Live page: https://craftech360-projects.github.io/cheeko-video-library/

The video links point to the "cheeko ai videos" Google Drive folder, so they open only for people that folder is shared with.

## Updating

This page is generated. Don't edit `index.html` by hand. After new videos are published to Drive (`marketing/tools/publish_to_drive.py`), run `marketing/tools/deploy_library.sh`. It rebuilds the page with `library_page.py --site` and pushes it here; GitHub Pages serves it within a minute or two.

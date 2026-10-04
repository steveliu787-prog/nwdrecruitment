# New World Recruitment UX Prototype

This repository hosts a single-page recruitment site prototype for the UX/UI academic redesign project.

- Live site: https://steveliu787-prog.github.io/nwdrecruitment/
- Main page: `index.html`
- Images: `assets/images/`
- Remote content edits: `edits.json`

## Open the in-page editor

Use one of these methods while viewing the live site:

- Press `Ctrl + Shift + E` on Windows/Linux, or `Cmd + Shift + E` on macOS.
- Add `#editor` to the end of the site URL.

The normal page layout stays visible. While editing is enabled, click any outlined text or image where it appears on the page.

- Text opens directly in place. Choose **完成** to save or **取消** to restore the previous text.
- Images open a floating crop panel. Drag the image to reposition it and use the zoom slider. The exported image keeps the same ratio as its page slot, so the layout does not shift.
- The toolbar supports Simplified Chinese, Traditional Chinese, and English. Each language has its own editable text layer.

When opening `index.html` directly with `file://`, browser security blocks cropping an image that is already loaded from disk. Select that image again with **从电脑选择图片** to crop it, or open the GitHub Pages URL where the same-origin images crop directly.

## Sync edits to GitHub

1. Edit text or images in place.
2. Select **保存到浏览器** to preview and save locally.
3. Select **同步到 GitHub** and enter a GitHub personal access token.

The token is stored only in the current browser session and is not written to the site or repository. The page updates `edits.json` through the GitHub Contents API, and GitHub Pages publishes the changes automatically.

The token needs permission to read and write repository contents. For a classic token, use `repo` or `public_repo`. For a fine-grained token, grant **Contents: Read and write** on this repository.

## Local preview

Open `index.html` directly in a browser. GitHub synchronisation is disabled for local file previews; browser-only edits still work.

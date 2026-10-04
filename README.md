# New World Recruitment UX Prototype

This repository hosts a single-page recruitment site prototype for the UX/UI academic redesign project.

- Live site: https://steveliu787-prog.github.io/nwdrecruitment/
- Main page: `index.html`
- Images: `assets/images/`
- Remote content edits: `edits.json`

## Open the hidden editor

Use one of these methods:

- Press `Ctrl + Shift + E` on Windows/Linux, or `Cmd + Shift + E` on macOS.
- Add `#editor` to the end of the site URL.

The editor can update visible images and text for Simplified Chinese, Traditional Chinese, and English. Changes are first saved in the browser, then written back to `edits.json` in this repository.

## Sync edits to GitHub

1. Open the hidden editor.
2. Choose the language tab for the content you want to edit.
3. Change the image URL or text fields.
4. Select **保存到浏览器** to preview and save locally.
5. Select **同步到 GitHub** and enter a GitHub personal access token.

The token is stored only in the current browser session and is not written to the site or repository.

The token needs permission to read and write repository contents. For a classic token, use `repo` or `public_repo`. For a fine-grained token, grant **Contents: Read and write** on this repository.

## Local preview

Open `index.html` directly in a browser. GitHub synchronisation is disabled for local file previews; browser-only edits still work.

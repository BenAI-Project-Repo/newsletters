# Newsletters

Published issues, hosted with **GitHub Pages**.

🔗 **Live site:** https://benai-project-repo.github.io/newsletters/

Each newsletter is a self-contained HTML file (images embedded), so the links
work anywhere and forever without a server.

## How issues get here

Newsletters are written with the WAT `/newsletter` pipeline and saved as local
**drafts** first. Nothing lands in this repo automatically — an issue is copied
here and pushed **only after it's explicitly approved**, one file at a time, via
`tools/publish_newsletter.py` in the Workflow project. See
`workflows/publish_newsletter.md` there for the process.

`index.html` (the landing page) is generated automatically from the newsletter
files in this folder — don't edit it by hand.

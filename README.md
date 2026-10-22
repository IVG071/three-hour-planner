# Three-hour package planner

A single-page tool for sketching a learning package as parts with minutes. Works offline once loaded; nothing is uploaded.

## Publish on GitHub Pages
1. Create a repository and upload `index.html` and the `vendor/` folder (keep the folder structure).
2. Settings > Pages > Deploy from branch > `main` / root.
3. Share the Pages URL with learners.

Exports: Word (.docx), PowerPoint (.pptx), PDF (via the browser print dialog) and a .json file for reopening a saved plan. Progress also autosaves in the learner's own browser.

`vendor/` holds the browser builds of [docx](https://github.com/dolanmiu/docx) and [PptxGenJS](https://github.com/gitbrent/PptxGenJS) so the page has no external dependencies.

# Rupesh Rajak: Digital Humanities Portfolio

This repository holds the portfolio website of **Rupesh Rajak**, MA in Digital Humanities, Department of Humanities and Social Sciences (HSS), IIT (ISM) Dhanbad, Session 2026-27.

The page brings together four assignments. Each one has a short abstract, a screenshot of the work, its main figures, and links to its live website and its GitHub repository.

| No. | Assignment | Website | Repository |
| --- | --- | --- | --- |
| 01 | Extraction of Indian Cultural Elements using Retrieval-Augmented Generation | [Website](https://rupeshrajak456.github.io/RAG-WORK/) | [GitHub](https://github.com/Rupeshrajak456/RAG-WORK) |
| 02 | Sanskrit Stop Words | [Website](https://rupeshrajak456.github.io/Sanskrit_stopwords/) | [GitHub](https://github.com/Rupeshrajak456/Sanskrit_stopwords) |
| 03 | A synthetic reading of R. Austin Freeman's "The Magic Casket" | [Website](https://rupeshrajak456.github.io/synthetic_work/) | [GitHub](https://github.com/Rupeshrajak456/synthetic_work) |
| 04 | Veritale: An Evidence-Graded Skill for Telling History as a Story with Large Language Models | [Website](https://rupeshrajak456.github.io/skill-veritale/) | [GitHub](https://github.com/Rupeshrajak456/skill-veritale) |

## Files

All files sit at the same level. Keep them together in the root of the repository, because the page looks for the images next to it.

| File | What it is |
| --- | --- |
| `index.html` | The portfolio page. All the styles and the small script are inside this one file. |
| `rag-flora-fauna-analysis.png` | Screenshot for Assignment 01 (Analysis section of the RAG website). |
| `sanskrit-stopwords-analysis.png` | Screenshot for Assignment 02 (Analysis table of the stop-word website). |
| `magic-casket-theme-density.png` | Screenshot for Assignment 03 (Figure A2, theme density across 13 segments). |
| `veritale-graded-timeline.png` | Screenshot for Assignment 04 (Graded timeline for Hastings, 1066). |
| `README.md` | This file. |

Do not rename the images unless you also change the matching `src="..."` in `index.html`. File names on GitHub Pages are case-sensitive.

## How to publish on GitHub Pages

1. Sign in to GitHub and click **New repository**. Give it a name (for example `DH-portfolio`), set it to **Public** and click **Create repository**.
2. On the new repository page, click **uploading an existing file** (or **Add file > Upload files**).
3. Drag all six files into the upload box at once. Do not put them inside a folder.
4. Write a short message such as "Add portfolio" and click **Commit changes**.
5. Open **Settings > Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the **main** branch and the **/ (root)** folder, then click **Save**.
6. Wait one or two minutes and refresh the page. GitHub will show the address of the site, which will look like this:

   `https://rupeshrajak456.github.io/<repository-name>/`

If you name the repository `rupeshrajak456.github.io`, the portfolio will open at `https://rupeshrajak456.github.io/` with nothing after the slash.

## Updating an existing repository

If the portfolio is already online, open the repository, click **Add file > Upload files**, drag in the new files and commit. Files with the same name are replaced. The site updates within a few minutes. If you still see the old version, press Ctrl + F5 (or Cmd + Shift + R on a Mac) to reload without the cache.

## Editing the page

- **Text:** open `index.html` in any text editor (Notepad, VS Code) or edit it directly on GitHub with the pencil icon.
- **Adding an assignment:** copy a whole `<article class="assignment"> ... </article>` block, paste it below the last one, and change the title, abstract, links, image and `data-site` address. The page numbers the assignments and rebuilds the "On this page" list by itself.
- **Links inside the page:** the "On this page" links to each assignment (`#assignment-1` and so on) are relative, so they work under whatever address the site is published at.
- **Dark mode and phones:** the page follows the reader's light or dark setting and fits narrow screens. No extra work is needed.

## Credits

Content, code and screenshots: Rupesh Rajak, 2026. Supervision: Shanmugapriya T. and Sourav Ghosh, Department of HSS, IIT (ISM) Dhanbad. The layout is based on the Digital Humanities Student Exhibition template of the Department of HSS, IIT (ISM) Dhanbad. Full references for each project are listed in the "Sources and acknowledgements" section of the page.

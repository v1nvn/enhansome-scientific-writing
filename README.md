# Awesome Scientific Writing [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome) ⭐ 438,405 | 🐛 71 | 📅 2026-01-28 with stars

> Scientific writing can extend beyond LaTeX, made possible by formats,
> such as
> [Markdown](https://daringfireball.net/projects/markdown/) (and its many flavours),
> [reStructuredText](https://docutils.sourceforge.io/rst.html) and
> [Jupyter notebooks](https://jupyter.org/).

:bookmark: means ability to **seamlessly cite references**.

:link: means ability to **cross-reference figures and sections within the
document**.

## Contents

* [Word Processors](#word-processors)
* [Bibliography](#bibliography)
* [Illustrations](#illustrations)
* [Converters and Filters](#converters-and-filters)
* [Spell Checking and Linting](#spell-checking-and-linting)
* [Templates](#templates)
  * [Articles](#articles)
  * [Presentations](#presentations)
  * [Books](#books)
* [Tutorials](#tutorials)
* [Other Lists](#other-lists)

## Word Processors

* [Marktext](https://github.com/marktext/marktext) ⭐ 53,903 | 🐛 1,390 | 🌐 JavaScript | 📅 2025-11-19 - Markdown text editor.
* [R Studio](https://github.com/rstudio/rstudio) ⭐ 4,948 | 🐛 1,369 | 🌐 Java | 📅 2026-02-19 - IDE for R.
  * [bookdown](https://github.com/rstudio/bookdown) ⭐ 4,009 | 🐛 230 | 🌐 JavaScript | 📅 2026-01-16 - R package to facilitate writing books and long-form articles, reports with R Markdown :bookmark: :link:.
  * [R Markdown](https://rmarkdown.rstudio.com/) - R package to write R next to Markdown :bookmark: :link:.
* [Visual Studio Code](https://code.visualstudio.com/) - Popular IDE with Markdown support.
  * [Markdown Preview Enhanced](https://github.com/shd101wyy/markdown-preview-enhanced) ⭐ 4,334 | 🐛 212 | 🌐 HTML | 📅 2025-01-29 - Pandoc
    integration and utilities.
  * [Markdown All in One](https://github.com/yzhang-gh/vscode-markdown/#readme) ⭐ 3,162 | 🐛 437 | 🌐 TypeScript | 📅 2025-03-09 - Extension for enhanced
    Markdown support in VSCode, such as preview and auto completion to name a few.
* [Vim](https://www.vim.org/) - Command line text editor.
  * [vim-pandoc](https://github.com/vim-pandoc/vim-pandoc) ⭐ 966 | 🐛 102 | 🌐 Vim Script | 📅 2025-11-07 - Pandoc integration and utilities for Vim.
  * [vim-pandoc-syntax](https://github.com/vim-pandoc/vim-pandoc-syntax) ⭐ 424 | 🐛 146 | 🌐 Vim Script | 📅 2025-09-22 - Pandoc syntax highlighting for Vim.
  * [fzf-bibtex](https://github.com/msprev/fzf-bibtex/#readme) ⭐ 130 | 🐛 0 | 🌐 Go | 📅 2024-07-25 - BibTeX source
    with Vim integration which uses fzf (a fuzzy finder implemented in Go).
* [Zettlr](https://www.zettlr.com/) - Markdown editor which
  integrates CSL, BibLaTeX, Pandoc and many other tools
  :bookmark: :link:.

## Bibliography

Reference managers to generate citations, BibTeX, and BibLaTeX files.

* [Citation Style Language (CSL) styles](https://editor.citationstyles.org/) - Crowdsourced
  repository with over 9000 free CSL citation styles and an online
  editor to create new ones.
* [JabRef](https://www.jabref.org/) - Open source bibliography reference manager.
* [Zotero](https://www.zotero.org/) - FOSS tool to collect, organize, cite, and
  share research.
  * [Better BibTeX for Zotero](https://retorque.re/zotero-better-bibtex/) - Enhanced
    BibTeX / BibLaTeX integration for Zotero.
  * [ZotFile for Zotero](http://zotfile.com/) - Enhanced PDF file management for Zotero.
* [ZoteroBib](https://zbib.org/) - Online bibliography reference manager.

## Illustrations

Drawing illustrations themselves has driven many a scientist mad. Fortunately,
there are formal languages with which one can create beautiful graphics.

* [app.diagrams.net](https://app.diagrams.net/) - Open source, online, desktop and
  container deployable diagramming software named draw\.io.
* [graphviz](https://graphviz.org/) - Visualization software for graphs and
  networks which uses a domain-specific DOT language.
* [Mermaid Live Editor](https://mermaid-js.github.io/mermaid-live-editor/) - Define simple diagrams instead of drawing them.
* [Vega Lite](https://vega.github.io/vega-lite/examples/) - Define charts and more complex diagrams.
* [PlantUML](https://plantuml.com/) - Define UML diagrams instead of drawing them.

## Converters and Filters

Supplementary files and tools.

* [Cicero](https://cicero.xyz/) - Python package which renders HTML presentations
  from Markdown source using remark or reveal.js :link:.
* [docutils](https://docutils.sourceforge.io/docs/) - Python package which can
  convert reStructuredText into various formats and provides command-line
  tools to do it :link:.
* [Jupyter Book](https://jupyterbook.org/en/stable/) - A static site generator which converts
  a collection of CommonMark, MyST markdown and Jupyter notebooks into a HTML website.
* [MyST](https://myst-parser.readthedocs.io/en/latest/) - Markedly Structured Text,
  a superset of CommonMark markdown with reStructuredText like features.
* [nbconvert](https://nbconvert.readthedocs.io/en/latest/) - Convert Jupyter
  notebooks into `reveal.js` presentations, PDF, HTML, Markdown,
  reStructuredText and more.
* [pandoc](https://pandoc.org/MANUAL) - Haskell library for converting from
  one markup format to another, and a command-line tool that uses this
  library :bookmark: :link:.
  * [Pandoc filters](https://github.com/jgm/pandoc/wiki/Pandoc-Filters) ⭐ 42,151 | 🐛 1,048 | 🌐 Haskell | 📅 2026-02-18 - List of
    addons to pandoc which implement extra features such as citations and
    cross-references.
  * [Academic Markdown](https://github.com/smathot/academicmarkdown#readme) ⭐ 354 | 🐛 3 | 🌐 Python | 📅 2021-05-24 - Python wrapper over Pandoc with specialized extensions to parse certain
    elements, making it a superset of Pandoc Markdown flavour :bookmark:
    :link:.
  * [Panflute](http://scorreia.com/software/panflute/) - Pythonic alternative
    to John MacFarlane's pandocfilters.
* [Quarto](https://quarto.org) - Compile R Markdown, and Jupyter Notebooks to PDFs, Slides and Websites. Supports R, Python, and Julia :bookmark: :link:.

## Spell Checking and Linting

* [Vale](https://github.com/errata-ai/vale) ⭐ 5,245 | 🐛 94 | 🌐 Go | 📅 2026-02-15 - Free, open-source linter for
  prose built with speed and extensibility in mind.
* [write-good](https://github.com/btford/write-good) ⭐ 5,061 | 🐛 25 | 🌐 JavaScript | 📅 2025-03-10 - Naive linter for English
  prose.
* [proselint](https://github.com/amperser/proselint) ⭐ 4,506 | 🐛 241 | 🌐 JavaScript | 📅 2026-01-26 - Linter for prose.
* [Markdown lint tool](https://github.com/markdownlint/markdownlint) ⭐ 2,008 | 🐛 153 | 🌐 Ruby | 📅 2025-12-01 - Markdown linter.
* [remarklint](https://github.com/remarkjs/remark-lint) ⭐ 1,021 | 🐛 5 | 🌐 JavaScript | 📅 2026-01-05 - Markdown linter.
* [restructuredtext-lint](https://github.com/twolfson/restructuredtext-lint) ⭐ 181 | 🐛 6 | 🌐 Python | 📅 2025-11-23 - reStructuredText linter.
* [LanguageCheck](https://github.com/JohannesBuchner/languagecheck) ⭐ 110 | 🐛 0 | 🌐 Python | 📅 2025-07-21 - Analyses scientific LaTeX papers, suggesting improvements from a list of common mistakes/ambiguities, tense consistency, a vs. an, spell check, and paragraph topic sentences.
* [GNU Aspell](http://aspell.net/) - Command line spell checker.
* [Hunspell](http://hunspell.github.io/) - Command line spell checker.
* [LanguageTool](https://languagetool.org/) - Open source grammar, style and
  spell Checker.
* [textlint](https://textlint.github.io/) - Pluggable linting tool for text
  and Markdown.
* [textidote](https://sylvainhalle.github.io/textidote/) - Spelling, grammar and
  style checking on LaTeX documents.

## Templates

Reusable minimalist examples.

### Articles

* [Steve's R Markdown Templates](https://github.com/svmiller/svm-r-markdown-templates/) ⭐ 929 | 🐛 19 | 🌐 HTML | 📅 2021-08-22 - Academic manuscript, memos, Beamer presentation, syllabus and CV.
* [Pandoc Markdown-LaTeX
  Boilerplate](https://github.com/davecap/markdown-latex-boilerplate/#readme) ⭐ 101 | 🐛 2 | 🌐 TeX | 📅 2018-05-07 - Demonstrate
  how to integrate Pandoc with an existing LaTeX template which
  requires some boilerplate code (i.e. LaTeX preamble), thus avoiding the
  `latexmk` dependency.
* [scientific-markdown](https://github.com/JensErat/scientific-markdown/#readme) ⭐ 54 | 🐛 0 | 🌐 TeX | 📅 2015-02-06 - Example
  for use of Markdown for scientific publications using Pandoc and
  `latexmk`.
* [Paper Templates for GitHub Pages](https://github.com/dev-onejun/paper-templates-for-github-pages) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2025-01-07 - Markdown-based templates for papers and RESUME/CVs, publishing with GitHub Pages.

### Presentations

* [pandoc-starter](https://github.com/jez/pandoc-starter/#readme) ⭐ 540 | 🐛 5 | 🌐 TeX | 📅 2021-07-11 - Templates for
  articles, Beamer presentations etc. using Markdown files and Makefiles for
  getting started with Pandoc.
* [slides](https://github.com/cgroll/slides/#readme) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2017-01-27 - Demo for generating `reveal.js`
  presentations using Pandoc.

### Books

* [Eisvogel](https://github.com/Wandmalfarbe/pandoc-latex-template) ⭐ 7,022 | 🐛 117 | 🌐 Shell | 📅 2026-02-08 - Clean academic pandoc LaTeX template.
* [Template for writing a PhD thesis in
  Markdown](https://github.com/tompollard/phd_thesis_markdown#readme) ⭐ 1,253 | 🐛 42 | 🌐 HTML | 📅 2023-05-23 - Clean
  organization of files to provide a framework for writing a PhD thesis in
  mostly Markdown with a little bit of LaTeX, and compiled with Pandoc.
* [bookdown-demo](https://github.com/rstudio/bookdown-demo/#readme) ⭐ 532 | 🐛 14 | 🌐 CSS | 📅 2024-10-23 - Minimal
  example of a book based on R Markdown and bookdown.

## Tutorials

How to generate articles and presentations for scientific purposes.

* [Teaching and learning with
  Jupyter](https://github.com/jupyter4edu/jupyter-edu-book/#readme) ⭐ 463 | 🐛 29 | 🌐 TeX | 📅 2023-03-30 - Book
  written in R Markdown, bookdown and also rendered as HTML, PDF and
  EPUB.
* [Book on Riemann solvers](https://github.com/clawpack/riemann_book/#readme) ⭐ 288 | 🐛 15 | 🌐 HTML | 📅 2025-11-30 - This
  example uses a custom `nbconvert` template and shows how to store your
  notebooks with no output (for version control) while automatically executing
  them before running `bookbook`, so that PDF and HTML versions include the
  output.
* [Katrin Leinweber's Ph.D.
  thesis](https://github.com/katrinleinweber/PhD-thesis/#readme) ⭐ 50 | 🐛 1 | 🌐 Shell | 📅 2021-10-20 - Automated
  work flow involving several tools, but primarily Pandoc, `latexmk` and
  Academic Markdown.
* [3 frameworks into one — Write your next paper with R Studio!](https://blog.devgenius.io/write-your-whole-paper-in-r-it-is-better-77e1843f0c09) - Article provides an overview to a workflow that combines R Markdown (bookdown), Zotero (literature management), and Notion (note taking on research papers) to write academic papers.
* [Dennis Tenen and Grant Wythoff](https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown) - Sustainable Authorship in Plain Text using Pandoc and Markdown.
* [Heads up! Quarto is here to stay. Immediately combine R & Python in your next document](https://blog.devgenius.io/heads-up-quarto-is-here-to-stay-aa861ef87491) - Summary of the capabilities of Quarto, why to use it, and how it compares to R Markdown. Also contains tips for M1 Mac users on how to fix a common problem with reticulate.
* [Scott Selisker](https://u.arizona.edu/~selisker/post/workflow/) - Plain Text Workflow for Academic Writing with Atom.
* [Write your dissertation in RMarkdown](https://ourcodingclub.github.io/tutorials/rmarkdown-dissertation/) - Step-by-step guide on creating a complex pdf document, including text, figures, references, images, formatting, and more.
* [Writing scientific papers for ACPD using Emacs
  Org-mode](https://www.draketo.de/english/emacs/writing-papers-in-org-mode-acpd) - Detailed
  tutorial on authoring a paper by seamlessly integrating with LaTeX
  commands within Org-mode.

## Other Lists

* [Awesome Jupyter](https://github.com/markusschanta/awesome-jupyter/#renderingpublishingconversion) ⭐ 4,541 | 🐛 6 | 📅 2026-02-19
* [Awesome LaTeX](https://github.com/egeerardyn/awesome-LaTeX/#readme) ⭐ 1,590 | 🐛 1 | 📅 2026-02-08
* [Awesome Markdown](https://github.com/BubuAnabelas/awesome-markdown/#readme) ⭐ 916 | 🐛 25 | 📅 2024-08-21
* [Delightful Open Science](https://codeberg.org/teaserbot-labs/delightful-open-science)

### Contribute

Contributions welcome! Read the [contribution guidelines](origin/CONTRIBUTING.md) first.

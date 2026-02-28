# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is the `gabybudel/gabybudel` GitHub profile repository. The `README.md` is automatically rendered on the GitHub profile page. It serves as an academic personal webpage showcasing publications, working papers, software, education, and contact information for Gabriel Budel (Ph.D. in AI and Network Science, TU Delft).

## Repository Structure

- **README.md** — The sole content file. Edited directly in Markdown. This is what GitHub renders on the profile page.
- **README.html** — A Pandoc-generated HTML version of the README (generated locally, not auto-built).

## Build / Generation

There is no build system, package manager, or CI/CD pipeline. To regenerate the HTML version:

```
pandoc README.md -s -o README.html
```

## Content Conventions

- Publications use full academic citation format with DOI links
- Working papers link to arXiv
- Software entries link to the hosting platform (Bitbucket, CRAN, GitHub)
- Sections are ordered: Publications, Working Papers, Ph.D. Thesis, Presentations, Software, Education, Contact

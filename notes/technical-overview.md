---
slug: github-napolitano-tseng-note-technical-overview
id: github-napolitano-tseng-note-technical-overview
title: napolitano-tseng Overview
repo: justin-napolitano/napolitano-tseng
githubUrl: https://github.com/justin-napolitano/napolitano-tseng
generatedAt: '2025-11-24T18:41:47.440Z'
source: github-auto
summary: >-
  The **napolitano-tseng** repository is a data-driven market research website.
  It's built with Hugo for fast static site generation, TailwindCSS for
  responsive styling, and Python for automation.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: note
entryLayout: note
showInProjects: false
showInNotes: true
showInWriting: false
showInLogs: false
---

The **napolitano-tseng** repository is a data-driven market research website. It's built with Hugo for fast static site generation, TailwindCSS for responsive styling, and Python for automation.

## Key Components:
- Static site generated using **Hugo**.
- Styling with **TailwindCSS** and processed by **PostCSS**.
- Automated build process via **Makefile** and **Python scripts**.
- Hosted on **Netlify** for continuous deployment.

## Quick Start:

### Prerequisites:
- Node.js and npm
- Python 3
- Hugo (v0.90.0)
- Make

### Installation:
```bash
git clone https://github.com/justin-napolitano/napolitano-tseng.git
cd napolitano-tseng
npm install
pip install -r requirements.txt
```

### Run Locally:
```bash
npm run watch:tw &
npm run watch:hugo
```

### Build for Production:
```bash
npm run build
# or
make clean
make html
```

**Gotcha:** Make sure your Hugo version is compatible. Missing dependencies can lead to errors during setup.

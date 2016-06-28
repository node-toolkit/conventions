# Project file conventions

This document describes the boilerplate files that should be included in toolkit projects.

**All projects**

All toolkit projects should contain the following files:

* `.editorconfig`: to ensure contributors' text editors automatically handle the coding and text conventions of each project
* `.gitattributes`: to ensure file attributes are correctly handled by git
* `.gitignore`: to ensure only wanted files are committed
* `.verb.md`: readme template, to ensure consistency, avoid errors, and to automatically generate related links, etc
* `LICENSE`: MIT license
* `README.md`

**Node.js**

When a JavaScript project is published to npm, the following files should be included:

* `.eslintrc.json`
* `.travis.yml`

**Recommended**

The following files should be added when applicable:

* `.github/contributing.md`
* `.github/issue_template.md`
* `.github/pull_request_template.md`

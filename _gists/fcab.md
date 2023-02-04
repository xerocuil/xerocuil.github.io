---
name:  "fcab"
description: Filing cabinet for documents.
requirements: printf,tar
download: https://gist.githubusercontent.com/xerocuil/d1c06a12353029ea81e89de380c82a18/raw/fcab.sh
source: https://gist.github.com/xerocuil/d1c06a12353029ea81e89de380c82a18
updated: 2023-01-14
---

**Usage**

Command                       | Description
-------                       | -----------
`fc.a <directory> <category>` | Add new folder file to `<category>` drawer in cabinet.
`fc.o <name>`                 | Open file from cabinet.
`fc.c <name>`                 | Close open file.
`fc.r <name>`                 | Remove folder file from cabinet.
`fc.v <patterns>`             | View contents of folder file (use with `<pattern>` to filter).
`fc.l`                        | List all folder files in cabinet.
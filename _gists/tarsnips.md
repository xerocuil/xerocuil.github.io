---
name:  "tarsnips"
description: Common Tarsnap functions.
requirements: tarsnap
download: https://gist.githubusercontent.com/xerocuil/97bcda6c09539c54ce46df9ca378a43e/raw/tarsnips.sh
source: https://gist.github.com/xerocuil/97bcda6c09539c54ce46df9ca378a43e
updated: 2023-10-24
---

**Usage**

`start.sh [COMMAND]`

If no command is given, the script will show the help message.

Command             | Description
:------             | :----------
`backup`            | Create archive with hostname and timestamp.
`keygen`            | Create Tarsnap key.
`list`              | List Tarsnap archives.
`remove <archive>`  | Delete archive.
`view <archive>`    | List contents of archive.
`help`              | Show this message.

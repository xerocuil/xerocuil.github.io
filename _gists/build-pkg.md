---
name:  "build-pkg"
description: Create Linux installation package.
requirements: tar, zenity
download: https://gist.githubusercontent.com/xerocuil/2a00dac2552ef638b8789c3a5f5f61af/raw/build-pkg.sh
source: https://gist.github.com/xerocuil/2a00dac2552ef638b8789c3a5f5f61af
updated: 2022-08-15
---

**Usage**

`build-pkg <package> <script_name>`

Argument        | Description
:-------        | :----------
`<package>`     | Directory containing package files
`<script_name>` | File name of package installer

**Example**

`build-pkg setup example-installer.sh`

**Package structure**

- setup/
  + data/
    * executable_file
  + docs/
    * icon.png
---
name:  "Gist Manager"
slug: gistman
version:
platform: Linux
language: shell
description: Repository-based bash script manager.
download: https://gist.githubusercontent.com/xerocuil/ddc1d655dc6d151abc39b71936a40b20/raw/f1f54d8354fc54262b0da8ee292ae2273248ae1b/gistman.sh
source: https://gist.github.com/xerocuil/ddc1d655dc6d151abc39b71936a40b20
demo:
img: icon.png
released: 2022-06-10
updated: 2023-10-24
---

## Usage

`gistman <command> <option>`

Command                   | Description
:------                   | :----------
`install <script-name>`   | Install script
`remove <script-name>`    | Remove script
`list`                    | List installed scripts
`listall`                 | List all scripts in repo
`update <script-name>`    | Update <script-name>
`updateall`               | Update all installed scripts

To add script from repository run:  
`gistman install <url>`

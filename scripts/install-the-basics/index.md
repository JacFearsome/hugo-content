---
title: install-the-basics.sh
summary: A script that installs basic tools
tags:
- Linux Administration
- Bash
- Packages
date: "2020-01-24T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Screenshot
  focal_point: Smart
links:
- icon: code
  icon_pack: fas
  name: Download Script
  url: https://raw.githubusercontent.com/JacFearsome/bash-scripts/master/install-scripts/install-the-basics.sh
---
This script installs a basic set of tools and common dependencies.
 - git
 - nano
 - curl
 - wget
 - unzip
 - net-tools
 - build-essential
 - apt-transport-https
 - software-properties-common
Usage Syntax:
```sh
curl -SSL https://jrussell.io/install-the-basics | sudo bash
```
Usage Example:
<script id="asciicast-310411" src="https://asciinema.org/a/310411.js" async></script>

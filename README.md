# kickstart

#### Table of Contents

1. [Overview](#overview)
2. [Script Descriptions](#script-descriptions)
    * [centos_7_workstation.cfg](#centos-7-workstation-script)
3. [Usage Tips](#usage-tips)
4. [Development - Guide for contributing to the module](#development)

## Overview

These are a collection of simple kickstart scripts that i have used in various forms as a base to provision systems over the years.
My hope is that someone can get some use out of them.

## Script Descriptions

### Centos 7 Workstation Script
This script builds a CentOS 7 Virtual (or physical) system with the following features.
..* LVM managed file system
..* Cinnamon UE
..* Luks encrypted system drive
..* GPT partitioning  scheme(BIOS or EFI boot)
..* BIOS device names

## Usage Tips
To use boot off the CentOS 7 Installation DVD and immediately press the tab key.
I host my kickstart files on an internal web server for ease of use but any of the standard methods of
referencing the kickstart file location will work e.g.
    ```ks=http://mycool.web.server/ks/centos_7_workstation.cfg```

    
## Development
Any of these Kickstart scripts can be improved and i welcome suggestions in 
the spirit of what they are...quick and dirty functional kickstart scripts.

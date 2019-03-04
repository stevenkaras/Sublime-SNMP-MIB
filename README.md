# Sublime SNMP MIB

A Sublime Text 3 extension for SNMP MIB files.

## Features

* Very basic syntax highlighting.
* Basic completions

## Install

### Install via the amazing [Package Control Plugin](https://sublime.wbond.net/)

* Bring up the Command Palette (Cmd + Shift + P on OS X, Ctrl + Shift + P on Windows).
* Select `Package Control: Install Package`
* Select `SNMP MIB` when the list appears.
* Package Control will automatically keep SNMP MIB up to date with the latest version.

### Manual Install

Clone this repo to your Packages directory

    git clone http://github.com/stevenkaras/Sublime-SNMP-MIB.git

On Mac this directory is located at `/Users/{user}/Library/Application\ Support/Sublime\ Text\ 3/Packages`.
On Windows this directory is located at `C:\Users\{user}\AppData\Roaming\Sublime Text 3\Packages`

## SNMP-MIB format

The SNMP-MIB format is sometimes called the SMI format, after the standard defined in RFCs 2578, 2579, and 2580.
The SMIv2 format as encoded here is an adapted subset of the ASN.1 syntax.

NOTE: the syntax here is not fully supported, and is just barely enough to support basic highlighting.
It was however tested on some real world examples of MIB files that are parsed by libsmi.

## Contributing

Pull requests welcome.

Ideas for low hanging fruit:

* extend the syntax to actually cover SMIv2 or at least ASN.1
* improve completions
* add syntax tests

## License

Copyright 2019 Steven Karas
Copyright 2016 qianbbbo

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

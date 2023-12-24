# Packer Bash Completion

**CAVE**: This completion is obsolete. Hashicorp tools bring their own shell
completion although it's opt-in by default. Consult the packer documentation on
[how to setup shell
completion](https://developer.hashicorp.com/packer/docs/commands#autocompletion).

## Overview

The script provides bash completion for [packer](http://www.packer.io)

## Features

* template filename completion (*.json) in current working dir
* support for basic options (i.e.. -debug)
* support for options with choices (i.e. -parallel=[true|false]

## Installation

Just copy the script to a decent place and source it in your `~/.bashrc` or `~/.profile`

    . <path-to>/packer

## Compatibility

The scirpt has been successfully tested with packer-0.6.0 and the
following OS:

- OS X 10.9 (bash < 4.0)
- CentOS-6.5 (bash > 4.0)
- Ubuntu 12.04 Server (bash > 4.0)

## Credits

The script technically is heavily inspired by the git-completion.bash
script. Kudos to Shawn O. Pearce <spearce@spearce.org> and all other
contributors for the inspiration and especially to the bash-completion
team in general.

## Copyright and License

This software is licensed under the MIT license. The license is provided in the [license file](https://github.com/mrolli/packer-bash-completion/blob/master/LICENSE).

Copyright (c) 2014 IT Services Department, University of Bern

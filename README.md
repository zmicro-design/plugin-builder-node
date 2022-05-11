# RSVM - Rust Version Manager Plugin for [ZMicro](https://github.com/zcorky/zmicro)

[![Release](https://img.shields.io/github/tag/zmicro-design/plugin-rsvm.svg?label=Release)](https://github.com/zmicro-design/plugin-rsvm/tags)
[![Build Status](https://github.com/zmicro-design/plugin-rsvm/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/zmicro-design/plugin-rsvm/actions/workflows/test.yml)
[![GitHub issues](https://img.shields.io/github/issues/zmicro-design/plugin-rsvm.svg)](https://github.com/zmicro-design/plugin-rsvm/issues)


## Installation

To install the package, run:
```bash
zmicro plugin install rsvm
```

### If you donot install [ZMicro](https://github.com/zcorky/zmicro):

```bash
# CURL
curl -o- https://raw.githubusercontent.com/zmicro-design/plugin-rsvm/master/install | bash

# WGET
wget -qO- https://raw.githubusercontent.com/zmicro-design/plugin-rsvm/master/install | bash
```

## Usage

```markdown
Rust Version Manager (v1.0.4)

Rust Version Manager is a tool for managing multiple Go versions.

Usage:
  zrsvm install <version>   - Install Rust version
  zrsvm use <version>       - Use Rust version
  zrsvm remove <version>    - Remove Rust version
  zrsvm ls                  - List the Go versions installed
  zrsvm ls-remote           - List all Go versions from remote
  zrsvm current             - Show current Rust version
  zrsvm exec                - Enter new shell with rust version for tmp
  zrsvm help                - Show help

Example:
  zrsvm install v16.14.2
  zrsvm use v16.14.2
  zrsvm remove v16.14.2
  zrsvm ls
  zrsvm ls-remote
  zrsvm current
```

## License
ZMicro Design is released under the [MIT License](./LICENSE).

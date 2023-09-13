# asdf-clang
<!--
[![CI](https://github.com/asdf-community/asdf-golang/actions/workflows/main.yml/badge.svg)](https://github.com/asdf-community/asdf-golang/actions/workflows/main.yml) -->

clang plugin for [asdf version manager](https://github.com/asdf-vm/asdf)

## Requirements

### MacOS

* [GNU Core Utils](http://www.gnu.org/software/coreutils/coreutils.html) - `brew install coreutils`
* [jq](https://jqlang.github.io/jq/) - `brew install jq`
### Linux (Debian)

* [GNU Core Utils](http://www.gnu.org/software/coreutils/coreutils.html) - `apt install coreutils`
* [curl](https://curl.haxx.se) - `apt install curl`
* [jq](https://jqlang.github.io/jq/) - `apt install jq`

## Install

```bash
asdf plugin add clang https://github.com/asdf-community/asdf-clang.git
```

## Contributing

Contributions welcome!

1. Install `asdf` tools

    ```shell
    asdf plugin add shellcheck https://github.com/luizm/asdf-shellcheck.git
    asdf plugin add shfmt https://github.com/luizm/asdf-shfmt.git
    asdf install
    ```

1. Develop!

1. Lint & Format

    ```shell
    ./scripts/format.bash
    ./scripts/lint.bash
    ```

1. PR changes

## Issues

* Assumes Linux, FreeBSD, or Mac
* Assumes x86_64, i386, i686, armv6l, armv7l, arm64 and ppc64le

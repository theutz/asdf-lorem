<div align="center">

# asdf-lorem [![Build](https://github.com/theutz/asdf-lorem/actions/workflows/build.yml/badge.svg)](https://github.com/theutz/asdf-lorem/actions/workflows/build.yml) [![Lint](https://github.com/theutz/asdf-lorem/actions/workflows/lint.yml/badge.svg)](https://github.com/theutz/asdf-lorem/actions/workflows/lint.yml)

[lorem](https://github.com/per9000/lorem) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- A `python` executable must exist in your path

# Install

Plugin:

```shell
asdf plugin add lorem
# or
asdf plugin add lorem https://github.com/theutz/asdf-lorem.git
```

lorem:

```shell
# Show all installable versions
asdf list-all lorem

# Install specific version
asdf install lorem latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lorem latest

# Now lorem commands are available
lorem --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/theutz/asdf-lorem/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Michael Utz](https://github.com/theutz/)

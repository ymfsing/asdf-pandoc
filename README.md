<div align="center">

# asdf-pandoc [![Build](https://github.com/aksdb/asdf-pandoc/actions/workflows/build.yml/badge.svg)](https://github.com/aksdb/asdf-pandoc/actions/workflows/build.yml) [![Lint](https://github.com/aksdb/asdf-pandoc/actions/workflows/lint.yml/badge.svg)](https://github.com/aksdb/asdf-pandoc/actions/workflows/lint.yml)


[pandoc](https://pandoc.org/getting-started.html) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add pandoc
# or
asdf plugin add pandoc https://github.com/aksdb/asdf-pandoc.git
```

pandoc:

```shell
# Show all installable versions
asdf list-all pandoc

# Install specific version
asdf install pandoc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pandoc latest

# Now pandoc commands are available
pandoc --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/aksdb/asdf-pandoc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Andreas Schneider](https://github.com/aksdb/)

<div align="center">

# asdf-ghorg [![Build](https://github.com/gbloquel/asdf-ghorg/actions/workflows/build.yml/badge.svg)](https://github.com/gbloquel/asdf-ghorg/actions/workflows/build.yml) [![Lint](https://github.com/gbloquel/asdf-ghorg/actions/workflows/lint.yml/badge.svg)](https://github.com/gbloquel/asdf-ghorg/actions/workflows/lint.yml)


[ghorg](https://github.com/gabrie30/ghorg) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add ghorg
# or
asdf plugin add ghorg https://github.com/gbloquel/asdf-ghorg.git
```

ghorg:

```shell
# Show all installable versions
asdf list-all ghorg

# Install specific version
asdf install ghorg latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ghorg latest

# Now ghorg commands are available
ghorg version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gbloquel/asdf-ghorg/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Gregory Bloquel](https://github.com/gbloquel/)

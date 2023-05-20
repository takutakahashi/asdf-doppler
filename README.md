<div align="center">

# asdf-doppler [![Build](https://github.com/takutakahashi/asdf-doppler/actions/workflows/build.yml/badge.svg)](https://github.com/takutakahashi/asdf-doppler/actions/workflows/build.yml) [![Lint](https://github.com/takutakahashi/asdf-doppler/actions/workflows/lint.yml/badge.svg)](https://github.com/takutakahashi/asdf-doppler/actions/workflows/lint.yml)


[doppler](https://docs.doppler.com/docs/install-cli) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add doppler
# or
asdf plugin add doppler https://github.com/takutakahashi/asdf-doppler.git
```

doppler:

```shell
# Show all installable versions
asdf list-all doppler

# Install specific version
asdf install doppler latest

# Set a version globally (on your ~/.tool-versions file)
asdf global doppler latest

# Now doppler commands are available
doppler --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/takutakahashi/asdf-doppler/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Takuya TAKAHASHI](https://github.com/takutakahashi/)

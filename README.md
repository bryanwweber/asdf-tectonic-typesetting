<div align="center">

# asdf-tectonic-typesetting [![Build](https://github.com/bryanwweber/asdf-tectonic-typesetting/actions/workflows/build.yml/badge.svg)](https://github.com/bryanwweber/asdf-tectonic-typesetting/actions/workflows/build.yml) [![Lint](https://github.com/bryanwweber/asdf-tectonic-typesetting/actions/workflows/lint.yml/badge.svg)](https://github.com/bryanwweber/asdf-tectonic-typesetting/actions/workflows/lint.yml)

[tectonic-typesetting](https://tectonic-typesetting.github.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Install](#install)
- [Contributing](#contributing)
- [License](#license)


# Install

Plugin:

```shell
asdf plugin add tectonic-typesetting
# or
asdf plugin add tectonic-typesetting https://github.com/bryanwweber/asdf-tectonic-typesetting.git
```

tectonic-typesetting:

```shell
# Show all installable versions
asdf list-all tectonic-typesetting

# Install specific version
asdf install tectonic-typesetting latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tectonic-typesetting latest

# Now tectonic-typesetting commands are available
tectonic --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bryanwweber/asdf-tectonic-typesetting/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Bryan Weber](https://github.com/bryanwweber/)

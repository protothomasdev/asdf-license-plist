<div align="center">

# asdf-license-plist [![Build](https://github.com/protothomasdev/asdf-license-plist/actions/workflows/build.yml/badge.svg)](https://github.com/protothomasdev/asdf-license-plist/actions/workflows/build.yml) [![Lint](https://github.com/protothomasdev/asdf-license-plist/actions/workflows/lint.yml/badge.svg)](https://github.com/protothomasdev/asdf-license-plist/actions/workflows/lint.yml)

[license-plist](https://github.com/mono0926/LicensePlist) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `zip`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add license-plist
# or
asdf plugin add license-plist https://github.com/protothomasdev/asdf-license-plist.git
```

license-plist:

```shell
# Show all installable versions
asdf list-all license-plist

# Install specific version
asdf install license-plist latest

# Set a version globally (on your ~/.tool-versions file)
asdf global license-plist latest

# Now license-plist commands are available
license-plist --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/protothomasdev/asdf-license-plist/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Thomas Meyer](https://github.com/protothomasdev/)

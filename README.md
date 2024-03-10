<div align="center">

# asdf-cloak-swift [![Build](https://github.com/lordcodes/asdf-cloak-swift/actions/workflows/build.yml/badge.svg)](https://github.com/lordcodes/asdf-cloak-swift/actions/workflows/build.yml) [![Lint](https://github.com/lordcodes/asdf-cloak-swift/actions/workflows/lint.yml/badge.svg)](https://github.com/lordcodes/asdf-cloak-swift/actions/workflows/lint.yml)

[cloak-swift](https://github.com/lordcodes/cloak-swift) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add cloak-swift
# or
asdf plugin add cloak-swift https://github.com/lordcodes/asdf-cloak-swift.git
```

cloak-swift:

```shell
# Show all installable versions
asdf list-all cloak-swift

# Install specific version
asdf install cloak-swift latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cloak-swift latest

# Now cloak-swift commands are available
cloakswift version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/lordcodes/asdf-cloak-swift/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Andrew Lord](https://github.com/lordcodes/)

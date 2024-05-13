<div align="center">

# asdf-cmsis-toolbox [![Build](https://github.com/vhdirk/asdf-cmsis-toolbox/actions/workflows/build.yml/badge.svg)](https://github.com/vhdirk/asdf-cmsis-toolbox/actions/workflows/build.yml) [![Lint](https://github.com/vhdirk/asdf-cmsis-toolbox/actions/workflows/lint.yml/badge.svg)](https://github.com/vhdirk/asdf-cmsis-toolbox/actions/workflows/lint.yml)

[cmsis-toolbox](https://github.com/Open-CMSIS-Pack/cmsis-toolbox) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add cmsis-toolbox
# or
asdf plugin add cmsis-toolbox https://github.com/vhdirk/asdf-cmsis-toolbox.git
```

cmsis-toolbox:

```shell
# Show all installable versions
asdf list-all cmsis-toolbox

# Install specific version
asdf install cmsis-toolbox latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cmsis-toolbox latest

# Now cmsis-toolbox commands are available
cbuild -V
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/vhdirk/asdf-cmsis-toolbox/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Dirk Van Haerenborgh](https://github.com/vhdirk/)

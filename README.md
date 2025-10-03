<div align="center">

# asdf-kubetail [![Build](https://github.com/kubetail-org/asdf-kubetail/actions/workflows/build.yml/badge.svg)](https://github.com/kubetail-org/asdf-kubetail/actions/workflows/build.yml) [![Lint](https://github.com/kubetail-org/asdf-kubetail/actions/workflows/lint.yml/badge.svg)](https://github.com/kubetail-org/asdf-kubetail/actions/workflows/lint.yml)

[kubetail](https://github.com/kubetail-org/kubetail) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add kubetail
# or
asdf plugin add kubetail https://github.com/kubetail-org/asdf-kubetail.git
```

kubetail:

```shell
# Show all installable versions
asdf list-all kubetail

# Install specific version
asdf install kubetail latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kubetail latest

# Now kubetail commands are available
kubetail --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kubetail-org/asdf-kubetail/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Andres Morey](https://github.com/kubetail-org/)

<div align="center">

# asdf-versio [![Build](https://github.com/pdemagny/asdf-versio/actions/workflows/build.yml/badge.svg)](https://github.com/pdemagny/asdf-versio/actions/workflows/build.yml) [![Lint](https://github.com/pdemagny/asdf-versio/actions/workflows/lint.yml/badge.svg)](https://github.com/pdemagny/asdf-versio/actions/workflows/lint.yml)

[versio](https://github.com/chaaz/versio) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add versio
# or
asdf plugin add versio https://github.com/pdemagny/asdf-versio.git
```

versio:

```shell
# Show all installable versions
asdf list-all versio

# Install specific version
asdf install versio latest

# Set a version globally (on your ~/.tool-versions file)
asdf global versio latest

# Now versio commands are available
versio --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/pdemagny/asdf-versio/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Pierre Demagny](https://github.com/pdemagny/)

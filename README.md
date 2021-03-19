<div align="center">

# asdf-chamber ![Build](https://github.com/alanjjenkins/asdf-chamber/workflows/Build/badge.svg) ![Lint](https://github.com/alanjjenkins/asdf-chamber/workflows/Lint/badge.svg)

[chamber](https://github.com/segmentio/chamber) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add chamber
# or
asdf plugin add chamber https://github.com/alanjjenkins/asdf-chamber.git
```

chamber:

```shell
# Show all installable versions
asdf list-all chamber

# Install specific version
asdf install chamber latest

# Set a version globally (on your ~/.tool-versions file)
asdf global chamber latest

# Now chamber commands are available
chamber version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/alanjjenkins/asdf-chamber/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Alan Jenkins](https://github.com/alanjjenkins/)

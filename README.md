<div align="center">

# asdf-template [![Build](https://github.com/Edditoria/asdf-template/actions/workflows/build.yml/badge.svg)](https://github.com/Edditoria/asdf-template/actions/workflows/build.yml) [![Lint](https://github.com/Edditoria/asdf-template/actions/workflows/lint.yml/badge.svg)](https://github.com/Edditoria/asdf-template/actions/workflows/lint.yml)

[template](https://github.com/Edditoria/asdf-template) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add template
# or
asdf plugin add template https://github.com/Edditoria/asdf-template.git
```

template:

```shell
# Show all installable versions
asdf list-all template

# Install specific version
asdf install template latest

# Set a version globally (on your ~/.tool-versions file)
asdf global template latest

# Now template commands are available
asdf --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Edditoria/asdf-template/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Edditoria](https://github.com/Edditoria/)

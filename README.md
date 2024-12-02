<div align="center">

# asdf-gcm [![Build](https://github.com/coopernetes/asdf-gcm/actions/workflows/build.yml/badge.svg)](https://github.com/coopernetes/asdf-gcm/actions/workflows/build.yml) [![Lint](https://github.com/coopernetes/asdf-gcm/actions/workflows/lint.yml/badge.svg)](https://github.com/coopernetes/asdf-gcm/actions/workflows/lint.yml)

[git-credential-manager](https://github.com/git-ecosystem/git-credential-manager) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add gcm
# or
asdf plugin add gcm https://github.com/coopernetes/asdf-gcm.git
```

gcm:

```shell
# Show all installable versions
asdf list-all gcm

# Install specific version
asdf install gcm latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gcm latest

# Now gcm commands are available
git-credential-manager --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/coopernetes/asdf-gcm/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Thomas Cooper](https://github.com/coopernetes/)

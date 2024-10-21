<div align="center">

# asdf-docker-compose [![Build](https://github.com/rmgpinto/asdf-docker-compose/actions/workflows/build.yml/badge.svg)](https://github.com/rmgpinto/asdf-docker-compose/actions/workflows/build.yml) [![Lint](https://github.com/rmgpinto/asdf-docker-compose/actions/workflows/lint.yml/badge.svg)](https://github.com/rmgpinto/asdf-docker-compose/actions/workflows/lint.yml)

[docker-compose](https://rmgpinto/asdf-docker-compose) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

 `bash`, `curl` and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add docker-compose
# or
asdf plugin add docker-compose https://github.com/rmgpinto/asdf-docker-compose.git
```

docker-compose:

```shell
# Show all installable versions
asdf list-all docker-compose

# Install specific version
asdf install docker-compose latest

# Set a version globally (on your ~/.tool-versions file)
asdf global docker-compose latest

# Now docker-compose commands are available
docker compose version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rmgpinto/asdf-docker-compose/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ricardo Pinto](https://github.com/rmgpinto/)

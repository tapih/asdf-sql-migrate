<div align="center">

# asdf-sql-migrate [![Build](https://github.com/tapih/asdf-sql-migrate/actions/workflows/build.yml/badge.svg)](https://github.com/tapih/asdf-sql-migrate/actions/workflows/build.yml) [![Lint](https://github.com/tapih/asdf-sql-migrate/actions/workflows/lint.yml/badge.svg)](https://github.com/tapih/asdf-sql-migrate/actions/workflows/lint.yml)

[sql-migrate](https://github.com/tapih/sql-migrate) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add sql-migrate
# or
asdf plugin add sql-migrate https://github.com/tapih/asdf-sql-migrate.git
```

sql-migrate:

```shell
# Show all installable versions
asdf list-all sql-migrate

# Install specific version
asdf install sql-migrate latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sql-migrate latest

# Now sql-migrate commands are available
sql-migrate --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tapih/asdf-sql-migrate/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Hiroshi Muraoka](https://github.com/tapih/)

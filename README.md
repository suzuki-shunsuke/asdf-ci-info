<div align="center">

# asdf-ci-info [![Build](https://github.com/suzuki-shunsuke/asdf-ci-info/actions/workflows/build.yml/badge.svg)](https://github.com/suzuki-shunsuke/asdf-ci-info/actions/workflows/build.yml) [![Lint](https://github.com/suzuki-shunsuke/asdf-ci-info/actions/workflows/lint.yml/badge.svg)](https://github.com/suzuki-shunsuke/asdf-ci-info/actions/workflows/lint.yml)


[ci-info](https://github.com/suzuki-shunsuke/ci-info) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add ci-info
# or
asdf plugin add ci-info https://github.com/suzuki-shunsuke/asdf-ci-info.git
```

ci-info:

```shell
# Show all installable versions
asdf list-all ci-info

# Install specific version
asdf install ci-info latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ci-info latest

# Now ci-info commands are available
ci-info --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/suzuki-shunsuke/asdf-ci-info/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Shunsuke Suzuki](https://github.com/suzuki-shunsuke/)

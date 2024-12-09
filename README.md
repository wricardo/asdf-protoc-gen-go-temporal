<div align="center">

# asdf-protoc-gen-go-temporal [![Build](https://github.com/wricardo/asdf-protoc-gen-go-temporal/actions/workflows/build.yml/badge.svg)](https://github.com/wricardo/asdf-protoc-gen-go-temporal/actions/workflows/build.yml) [![Lint](https://github.com/wricardo/asdf-protoc-gen-go-temporal/actions/workflows/lint.yml/badge.svg)](https://github.com/wricardo/asdf-protoc-gen-go-temporal/actions/workflows/lint.yml)

[protoc-gen-go-temporal](https://github.com/wricardo/protoc-gen-go-temporal) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add protoc-gen-go-temporal
# or
asdf plugin add protoc-gen-go-temporal https://github.com/wricardo/asdf-protoc-gen-go-temporal.git
```

protoc-gen-go-temporal:

```shell
# Show all installable versions
asdf list-all protoc-gen-go-temporal

# Install specific version
asdf install protoc-gen-go-temporal latest

# Set a version globally (on your ~/.tool-versions file)
asdf global protoc-gen-go-temporal latest

# Now protoc-gen-go-temporal commands are available
protoc-gen-go-temporal --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/wricardo/asdf-protoc-gen-go-temporal/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Wallace Ricardo](https://github.com/wricardo/)

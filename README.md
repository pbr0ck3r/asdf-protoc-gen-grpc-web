<div align="center">

# asdf-protoc-gen-grpc-web [![Build](https://github.com/pbr0ck3r/asdf-protoc-gen-grpc-web/actions/workflows/build.yml/badge.svg)](https://github.com/pbr0ck3r/asdf-protoc-gen-grpc-web/actions/workflows/build.yml) [![Lint](https://github.com/pbr0ck3r/asdf-protoc-gen-grpc-web/actions/workflows/lint.yml/badge.svg)](https://github.com/pbr0ck3r/asdf-protoc-gen-grpc-web/actions/workflows/lint.yml)


[protoc-gen-grpc-web](https://github.com/pbr0ck3r/protoc-gen-grpc-web) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add protoc-gen-grpc-web
# or
asdf plugin add protoc-gen-grpc-web https://github.com/pbr0ck3r/asdf-protoc-gen-grpc-web.git
```

protoc-gen-grpc-web:

```shell
# Show all installable versions
asdf list-all protoc-gen-grpc-web

# Install specific version
asdf install protoc-gen-grpc-web latest

# Set a version globally (on your ~/.tool-versions file)
asdf global protoc-gen-grpc-web latest

# Now protoc-gen-grpc-web commands are available
protoc-gen-grpc-web --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/pbr0ck3r/asdf-protoc-gen-grpc-web/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Phil Brocker](https://github.com/pbr0ck3r/)

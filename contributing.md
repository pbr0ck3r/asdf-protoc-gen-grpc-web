# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test protoc-gen-grpc-web https://github.com/pbr0ck3r/asdf-protoc-gen-grpc-web.git "protoc-gen-grpc-web --version"
```

Tests are automatically run in GitHub Actions on push and PR.

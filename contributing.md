# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test protoc-gen-go-temporal https://github.com/wricardo/asdf-protoc-gen-go-temporal.git "protoc-gen-go-temporal --version"
```

Tests are automatically run in GitHub Actions on push and PR.

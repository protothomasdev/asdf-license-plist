# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test license-plist https://github.com/protothomasdev/asdf-license-plist.git "license-plist --version"
```

Tests are automatically run in GitHub Actions on push and PR.

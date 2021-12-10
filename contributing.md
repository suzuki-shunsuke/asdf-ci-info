# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test ci-info https://github.com/suzuki-shunsuke/asdf-ci-info.git "ci-info --help"
```

Tests are automatically run in GitHub Actions on push and PR.

<div align="center">

# asdf-meshctl [![Build](https://github.com/shpwrck/asdf-meshctl/actions/workflows/build.yml/badge.svg)](https://github.com/shpwrck/asdf-meshctl/actions/workflows/build.yml) [![Lint](https://github.com/shpwrck/asdf-meshctl/actions/workflows/lint.yml/badge.svg)](https://github.com/shpwrck/asdf-meshctl/actions/workflows/lint.yml)

[meshctl](https://docs.solo.io/gloo-mesh-enterprise/latest/reference/cli/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add meshctl
# or
asdf plugin add meshctl https://github.com/shpwrck/asdf-meshctl.git
```

meshctl:

```shell
# Show all installable versions
asdf list-all meshctl

# Install specific version
asdf install meshctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global meshctl latest

# Now meshctl commands are available
meshctl version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/shpwrck/asdf-meshctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jason Skrzypek](https://github.com/shpwrck/)

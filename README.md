<div align="center">

# asdf-gawk [![Build](https://github.com/StorageMatt/asdf-gawk/actions/workflows/build.yml/badge.svg)](https://github.com/StorageMatt/asdf-gawk/actions/workflows/build.yml) [![Lint](https://github.com/StorageMatt/asdf-gawk/actions/workflows/lint.yml/badge.svg)](https://github.com/StorageMatt/asdf-gawk/actions/workflows/lint.yml)


[gawk](http://git.savannah.gnu.org/cgit/gawk.git) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add gawk
# or
asdf plugin add gawk https://github.com/StorageMatt/asdf-gawk.git
```

gawk:

```shell
# Show all installable versions
asdf list-all gawk

# Install specific version
asdf install gawk latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gawk latest

# Now gawk commands are available
gawk --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/StorageMatt/asdf-gawk/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Matt](https://github.com/StorageMatt/)

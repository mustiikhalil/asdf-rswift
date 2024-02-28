<div align="center">

# asdf-rswift [![Build](https://github.com/mustiikhalil/asdf-rswift/actions/workflows/build.yml/badge.svg)](https://github.com/mustiikhalil/asdf-rswift/actions/workflows/build.yml) [![Lint](https://github.com/mustiikhalil/asdf-rswift/actions/workflows/lint.yml/badge.svg)](https://github.com/mustiikhalil/asdf-rswift/actions/workflows/lint.yml)

[rswift](https://github.com/mac-cain13/R.swift) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add rswift
# or
asdf plugin add rswift https://github.com/mustiikhalil/asdf-rswift.git
```

rswift:

```shell
# Show all installable versions
asdf list-all rswift

# Install specific version
asdf install rswift latest

# Set a version globally (on your ~/.tool-versions file)
asdf global rswift latest

# Now rswift commands are available
rswift --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mustiikhalil/asdf-rswift/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Mustafa Khalil](https://github.com/mustiikhalil/)

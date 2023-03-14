<div align="center">

# asdf-twitch [![Build](https://github.com/mimikun/asdf-twitch/actions/workflows/build.yml/badge.svg)](https://github.com/mimikun/asdf-twitch/actions/workflows/build.yml) [![Lint](https://github.com/mimikun/asdf-twitch/actions/workflows/lint.yml/badge.svg)](https://github.com/mimikun/asdf-twitch/actions/workflows/lint.yml)


[twitch](https://github.com/twitchdev/twitch-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add twitch
# or
asdf plugin add twitch https://github.com/mimikun/asdf-twitch.git
```

twitch:

```shell
# Show all installable versions
asdf list-all twitch

# Install specific version
asdf install twitch latest

# Set a version globally (on your ~/.tool-versions file)
asdf global twitch latest

# Now twitch commands are available
twitch version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](CONTRIBUTING.md).

[Thanks goes to these contributors](https://github.com/mimikun/asdf-twitch/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mimikun](https://github.com/mimikun/)

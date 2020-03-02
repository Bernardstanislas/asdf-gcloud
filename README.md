<div align="center">

# asdf-gcloud ![Shellcheck](https://github.com/jthegedus/asdf-gcloud/workflows/Shellcheck/badge.svg)

GCloud CLI plugin for [asdf](https://asdf-vm.com) version manager.

</div>

# Quickstart

```shell
asdf plugin add gcloud
```

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- Python 2 or Python 3.
- set `CLOUDSDK_PYTHON` environment variable in your shell config to load the correct version of Python.

# Install

Plugin:

```shell
asdf plugin add gcloud
# or
asdf plugin add https://github.com/jthegedus/asdf-gcloud.git
```

GCloud:

```shell
asdf install gcloud 282.0.0
```

Set global version:

```shell
asdf global gcloud 282.0.0
```

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jthegedus/asdf-gcloud/graphs/contributors)!

# License

[MIT License](LICENSE) © [James Hegedus](https://github.com/jthegedus/)

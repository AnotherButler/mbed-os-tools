# Mbed OS Tools

This repository contains the python modules needed to work with Mbed OS. Historically, the Mbed OS tools have been delivered in separate packages and repositories. Their APIs have evolved separately over time, each with their own style and syntax. This project is working to unify these packages into a single intuitive API.

## Packages

Below is a table showing what packages are delivered from this repository:

| PyPI Package | Source | Depends on | Stable API |
| ------- | ------ | ---------- | ---------- |
| mbed-os-tools | `src/` | | **No** |
| mbed-ls | `packages/mbed-ls/` | mbed-os-tools | **Yes** |
| mbed-host-tests | `packages/mbed-host-tests/` | mbed-os-tools | **Yes** |
| mbed-greentea | `packages/mbed-greentea/` | mbed-os-tools | **Yes** |

As indicated above, **the API provided by `mbed-os-tools` is not stable**. For this reason, please continue to use the other packages.

## License and contributions

The software is provided under [Apache-2.0 license](LICENSE). Contributions to this project are accepted under the same license. Please see [contributing.md](CONTRIBUTING.md) for more info.

This project contains code from other projects. The original license text is included in those source files. They must comply with our [license guide](https://os.mbed.com/docs/latest/reference/license.html).

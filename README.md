# pcb-main-nautilus-atmega4809
[![CI](https://github.com/apcountryman/pcb-main-nautilus-atmega4809/actions/workflows/ci.yml/badge.svg)](https://github.com/apcountryman/pcb-main-nautilus-atmega4809/actions/workflows/ci.yml)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](CODE_OF_CONDUCT.md)

A Microchip ATmega4809 based mainboard PCB that uses a form factor similar to the Arduino
Uno Rev3.

## Obtaining the Source Code
HTTPS:
```shell
git clone --recurse-submodules https://github.com/apcountryman/pcb-main-nautilus-atmega4809.git
```
SSH:
```shell
git clone --recurse-submodules git@github.com:apcountryman/pcb-main-nautilus-atmega4809.git
```

## Board Setup
The board setup uses OSH Park's 4 layer board stackup and design rules which can be found
at https://docs.oshpark.com/services/ and https://docs.oshpark.com/services/four-layer/.

## Usage
This repository's Git `pre-commit` hook script is the simplest way to test this project
during development.
See the `pre-commit` script's help text for usage details.
```shell
./git/hooks/pre-commit --help
```

Additional checks, such as static analysis, are performed by this project's GitHub Actions
CI workflow.

## Versioning
`pcb-main-nautilus-atmega4809` follows the [Abseil Live at Head
philosophy](https://abseil.io/about/philosophy).

## Workflow
`pcb-main-nautilus-atmega4809` uses the [GitHub
flow](https://guides.github.com/introduction/flow/) workflow.

## Git Hooks
To install this repository's Git hooks, execute the `install` script located in the
`git/hooks` directory.
See the `install` script's help text for usage details.
```shell
./git/hooks/install --help
```

## Code of Conduct
`pcb-main-nautilus-atmega4809` has adopted the Contributor Covenant 2.0 code of conduct.
For more information, [see the `CODE_OF_CONDUCT.md` file in this
repository](CODE_OF_CONDUCT.md).

## Contributing
If you are interested in contributing to `pcb-main-nautilus-atmega4809`, please [read the
`CONTRIBUTING.md` file in this repository](CONTRIBUTING.md).

## Authors
- Andrew Countryman

## License
For licensing information, [see the `LICENSE.md` file in this repository](LICENSE.md).

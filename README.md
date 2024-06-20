# SintPowerCase.jl

This package is meant for reading power system data from different sources into data frames. The format is ispired by the MATPOWER case format. The package will also provide some power system matrices based on the data.

[![CI](https://img.shields.io/github/actions/workflow/status/SINTEF-Power-system-asset-management/SintPowerCase.jl/run_tests.yaml?branch=main&logo=github&label=CI)](https://github.com/SINTEF-Power-system-asset-management/SintPowerCase.jl/actions?query=event%3Apush+branch%3Amain+workflow%3A"Unit+tests")
[![](https://img.shields.io/badge/docs-latest-blue.svg)](https://sintef-power-system-asset-management.github.io/SintPowerCase.jl/)


## Documentation

Automatically generated documentation can be found at <https://sintef-power-system-asset-management.github.io/SintPowerCase.jl>.

## Developers guide

### Pre-commit

Pre-commit runs a script before commit. In this repo we use it to make sure the formatting is proper, because otherwise we will run into issues in CI. To install `pre-commit` run

```bash
pip install pre-commit # Installs pre-commit on your system
pre-commit install # Installs the hooks defined in .pre-commit-config.yaml to your .git folder
```

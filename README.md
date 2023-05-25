<div align="center">
<img src="images/opshin-linter.png" alt="OpShin Logo" width=200>
<h1>OpShin Linter</h1>
</div>

&nbsp;

## General Information

This extension shows you in real time if your [opshin] smart contract is valid and could be compiled to UPLC.

By using this extension you don't need to manually check every time if you are writing correct OpShin syntax.

For more information about writing Smart Contracts for Cardano with OpShin in Python, please refer to the [website of OpShin](https://opshin.dev/) or the [official repository](https://github.com/OpShin/opshin).

&nbsp;

## Installation

Please use check that you have the necessary versions installed:

- `opshin >= 0.14.0`
- `python >= 3.8, < 3.12`

&nbsp;

## Usage

To activate Linting support, add a shebang to the first line of the python file to indicate that it represents an opshin smart contract.
You can choose from the following options:

- a general shebang: `#!opshin`, which represents `opshin eval any`
- or a more specific purpose: `#!/usr/bin/env -S opshin eval minting`

&nbsp;

## Support

To contribute to this repository, please check out [DEVELOPMENT.md](https://github.com/OpShin/opshin-vscode/blob/main/DEVELOPMENT.md)

[opshin]: https://opshin.dev/

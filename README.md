[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (----------------------------------------------------)
[comment]: <> (Copyright © 2021, 2022, 2023,)
[comment]: <> (            2024, 2025, 2026)
[comment]: <> (            Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (----------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the)
[comment]: <> (GNU Affero General Public License as published)
[comment]: <> (by the Free Software Foundation, either version)
[comment]: <> (3 of the License.)

[comment]: <> (This program is distributed in the hope that it)
[comment]: <> (will be useful, but WITHOUT ANY WARRANTY;)
[comment]: <> (without even the implied warranty of)
[comment]: <> (MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.)
[comment]: <> (See the GNU Affero General Public License)
[comment]: <> (for more details.)

[comment]: <> (You should have received a copy of the)
[comment]: <> (GNU Affero General Public License)
[comment]: <> (with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# TOKEN

This is an ERC-20 smart contract by OpenZeppelin
as far as I know merged in
a single file.

This repository contains resources to work with
an ERC-20 smart contract on an Ethereum Virtual
Machine compatible network.

In particular it contains a
Javascript module which contains a load function
for ERC-20 contracts data, such as the ERC-20
contract source, its ABI and bytecode.

The data is generated at package build time
using
[Solidity Compiler](
  https://github.com/themartiancompany/solidity-compiler).

# Build

To build the module one can use GNU Make

```bash
make \
  build-npm
```

or npm

```bash
npm \
  install
```

# License

This originally MIT licensed file is distributed
under the GNU Affero General Public License version 3
by Pellegrino Prevete.

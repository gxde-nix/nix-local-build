# GXDE-NIX Local Package Build Script
This script will build the Nix package locally.

## Usage
```
Usage: build-nix [options] [target]

Build a Nix package from the current directory.

Options:
  -L, --log       Show full build logs.
      --rebuild   Rebuild to check reproducibility.
      --cleanup   Cleanup results.
  -h, --help      Print help page.

Target:
  A .nix file or a flake installable, such as .#package.
  Defaults to the target where this script is in.
```

## License
(C) 2026 CharOfString.

`build-nix` is licensed under [MIT](https://spdx.org/licenses/MIT.html) OR (at your opinion) [GPL-1.0-or-later](https://spdx.org/licenses/GPL-1.0-or-later.html).

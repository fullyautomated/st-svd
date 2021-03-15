# st-svd

A collection of Apache-2.0 licensed SVD files extracted from STM32CubeIDE.
The collection is manually updated whenever the debug plugin, and in turn the SVD files, are released.

## Updates

Feel free to open an issue when a new version is released, or open a PR.
The files were extracted from an STM32CubeIDE installed on Arch Linux as follows:

```sh
grep -rl --null --include "*.svd" "SPDX" /opt/stm32cubeide | xargs -0r cp -t /path/to/st-svd
```

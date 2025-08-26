# Neovim AppImage for arm64 (Ubuntu 20.04)

[![Build](https://github.com/ToshikiNakamura0412/neovim-linux-arm64-appimage/actions/workflows/build.yml/badge.svg)](https://github.com/ToshikiNakamura0412/neovim-linux-arm64-appimage/actions/workflows/build.yml)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This repository provides Neovim AppImage for arm64 (Ubuntu 20.04).

## Compatibility

The official Neovim AppImage requires a newer version of **glibc** (≥ 2.32),
which may not be available on older distributions.

This AppImage is built on **Ubuntu 20.04 (arm64)** and is compatible with
systems that provide older glibc versions (e.g. glibc 2.31).

👉 If you see errors like:
  ```
  /tmp/.mount_nvim-lfJKLCc/usr/bin/nvim: /lib/aarch64-linux-gnu/libc.so.6: version GLIBC_2.32' not found (required by /tmp/.mount_nvim-lfJKLCc/usr/bin/nvim)
  ```
please use this appimage.

## Installation

1. Download [nvim-linux-arm64.appimage](https://github.com/ToshikiNakamura0412/neovim-linux-arm64-appimage/releases/download/stable/nvim-linux-arm64.appimage) (the latest release).
2. Make it executable and run:

	```bash
	chmod +x nvim-linux-arm64.appimage
	./nvim-linux-arm64.appimage
	```

## License

This appImage is distributed under the [Apache 2.0 licene (Neovim)](https://github.com/neovim/neovim/blob/master/LICENSE.txt).

Neovim is developed by the [Neovim project](https://github.com/neovim/neovim.git).

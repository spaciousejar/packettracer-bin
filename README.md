# packettracer-bin

An Arch Linux (AUR) package for Cisco Packet Tracer 9.0

[![AUR](https://img.shields.io/aur/version/packettracer-bin?label=AUR&color=1793d1)](https://aur.archlinux.org/packages/packettracer-bin)
[![License](https://img.shields.io/badge/license-Proprietary-red)](https://www.netacad.com/courses/packet-tracer)

Cisco Packet Tracer is a network simulation tool that lets you experiment with network setups and configurations. This package makes it easy to install and run Packet Tracer on Arch Linux.

## Installation

The easiest way to install is using an AUR helper:

```bash
# Using yay
yay -S packettracer-bin
```

If you prefer to build it manually:

1. Clone the repository:
   ```bash
   git clone https://aur.archlinux.org/packettracer-bin.git
   cd packettracer-bin
   ```

2. Build and install:
   ```bash
   makepkg -si
   ```

## Usage

Once installed, you can start Packet Tracer in a few ways:

- From the command line:
  ```bash
  packettracer-bin
  ```

- From your application menu (look for "Cisco Packet Tracer")

Note that the first launch might take a bit longer as it sets up everything.

## Package Details

- Version: 9.0
- Architecture: x86_64
- Installation path: `/opt/pt/`
- Binary location: `/usr/local/bin/packettracer-bin`

This package uses the official Cisco Packet Tracer Debian package and sets up everything needed to run it on Arch. It creates desktop entries and command-line shortcuts automatically.


## License

Cisco Packet Tracer is proprietary software. Make sure to check the EULA during installation for the terms of use.

## Contributing

If you run into any issues or have ideas for improvements, feel free to open an issue on Github or  AUR package page.

---

**Maintainer:** spaciousejar

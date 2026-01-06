# packettracer-bin AUR Package

This is an AUR package for Cisco Packet Tracer 9.0.

## Installation

1. Clone this repository:
   ```bash
   git clone https://aur.archlinux.org/packettracer-bin.git
   cd packettracer-bin
   ```

2. Install the package:
   ```bash
   makepkg -si
   ```

## Notes

- This package uses the official Cisco Packet Tracer Debian package
- The application is installed to `/opt/pt/`
- Symlinks are created in `/usr/local/bin/` for easy access
- A desktop entry is created for GUI access

## Dependencies

The package depends on:
- coreutils
- fuse2
- zstd
- pcre2
- sudo
- xdg-utils
- gtk-update-icon-cache
- glibc
- gcc-libs
- bash

## License

Cisco Packet Tracer is proprietary software. Please refer to the EULA during installation.
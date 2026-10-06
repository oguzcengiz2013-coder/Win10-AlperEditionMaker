# Win10-AlperEditionMaker

Win10-AlperEditionMaker is a tool for creating customized Windows 10 installation ISOs from your own Windows 10 installation media.

It automates common ISO customization tasks and can optionally apply compatibility tweaks intended for older hardware.

> **Note:** The Windows 10 version is currently more experimental and may contain more bugs than Win11-AlperEditionMaker. Always test the generated ISO in a virtual machine or on non-critical hardware before using it on your main PC.

## Features

- Modify a Windows 10 ISO automatically
- Add custom files and folders
- Add `$OEM$` content
- Add setup scripts such as `SetupComplete.cmd` and first-logon scripts
- Integrate drivers
- Apply registry tweaks
- Add themes, wallpapers, icons, and other customizations
- Optional compatibility tweaks for older hardware
- Rebuild the modified installation media into a new ISO

## Requirements

- Windows 10
- Administrator privileges
- A legitimate Windows 10 ISO
- Enough free disk space for extracting and rebuilding the ISO

## Usage

1. Download or clone this repository.
2. Obtain a legitimate Windows 10 ISO.
3. Run Win10-AlperEditionMaker as Administrator.
4. Select or provide your Windows 10 ISO.
5. Configure the desired modifications.
6. Build the customized ISO.

## Older Hardware Compatibility

Win10-AlperEditionMaker may include optional Setup compatibility modifications intended for older hardware.

These modifications may include changes related to Windows Setup compatibility checks, including `appraiserres.dll`.

These tweaks do **not** bypass Windows activation or licensing.

Compatibility modifications are not guaranteed to work with every Windows 10 build or hardware configuration.

## Known Limitations

- The Windows 10 version may be less stable than the Windows 11 version.
- Some customization steps may fail on certain Windows 10 builds.
- Compatibility tweaks may behave differently depending on the ISO version.
- Testing in a virtual machine is recommended before installing on real hardware.

## Important

This repository does **not** include or distribute Microsoft Windows or Windows installation media.

It does not include:

- Windows ISO files
- `install.wim`
- `boot.wim`
- Windows product keys
- Activation tools
- KMS tools
- Cracks
- Activation bypasses
- Pre-activated Windows installations

Users must provide their own legitimate Windows 10 installation media.

## Disclaimer

Win10-AlperEditionMaker is an independent project and is not affiliated with, sponsored by, or endorsed by Microsoft Corporation.

Microsoft, Windows, and Windows 10 are trademarks of Microsoft Corporation.

Users are responsible for ensuring that their use of Windows and any third-party files complies with the applicable licenses and terms.

## License

The license included with this repository applies only to the original Win10-AlperEditionMaker code and files.

It does not grant any rights to Microsoft Windows or other third-party software.

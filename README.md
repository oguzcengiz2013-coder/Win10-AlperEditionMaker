# Win10-AlperEditionMaker

Win10-AlperEditionMaker is a tool for creating customized Windows 10 installation ISOs from your own Windows 10 installation media.

Optional drivers go in the $OEM$\$$\Setup\Scripts\Drivers folder.

It automates common ISO customization tasks and can optionally apply compatibility tweaks intended for older hardware.

> **Note:** Win10-AlperEditionMaker may have a few more compatibility quirks than Win11-AlperEditionMaker depending on the Windows 10 build and hardware configuration being used.

## Download

Download the latest release ZIP from the **[Releases](https://github.com/oguzcengiz2013-coder/Win10-AlperEditionMaker/releases) section.

Extract the ZIP before running the Maker.

## Features

- Modify a Windows 10 ISO automatically
- Add custom files and folders
- Add `$OEM$` content
- Add SetupComplete and first-logon scripts
- Apply registry tweaks
- Add themes, wallpapers, icons, and other customizations
- Support for manually provided drivers
- Optional compatibility tweaks for older hardware
- Rebuild the modified installation media into a new ISO

## Requirements

- Windows 10
- Administrator privileges
- A legitimate Windows 10 ISO
- Enough free disk space for extracting and rebuilding the ISO

## Usage

1. Download the latest release ZIP.
2. Extract the ZIP to a folder.
3. Obtain a legitimate Windows 10 ISO.
4. Run Win10-AlperEditionMaker as Administrator.
5. Select or provide your Windows 10 ISO.
6. Configure the desired modifications.
7. Build the customized ISO.

## Driver Support

Drivers are **not bundled** with Win10-AlperEditionMaker.

If you want to include additional drivers, manually place the required driver files in the appropriate driver folder before building the ISO.

If you do not need custom drivers, you can leave the driver folder unchanged.

## Older Hardware Compatibility

Win10-AlperEditionMaker may include optional Windows Setup compatibility modifications intended for older hardware.

These modifications may include changes related to Setup compatibility checks, including handling of `appraiserres.dll`.

These tweaks do **not** bypass Windows activation or licensing.

Compatibility modifications are not guaranteed to behave identically with every Windows 10 build or hardware configuration.

## Notes

- Behavior may vary between different Windows 10 builds.
- Some customization options may behave differently depending on the source ISO.
- Win10-AlperEditionMaker may have a few more compatibility quirks than the Windows 11 version.
- Testing the generated ISO in a virtual machine before installing it on important hardware is recommended.
- Always keep a backup of your original Windows 10 ISO.

## Important

This repository and its release ZIP files do **not** include or distribute Microsoft Windows or Windows installation media.

They do not include:

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

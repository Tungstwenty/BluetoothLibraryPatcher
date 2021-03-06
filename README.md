# Bluetooth Library Patcher

## Description

This module attends to avoid losing bluetooth pairings after reboot or airplane mode switch on rooted samsung devices.

It patches on the fly the bluetooth library and should support most of samsung devices on android Oreo, Pie and 10.

If it fails on your device, please post your /system/lib64/libbluetooth.so and /system/build.prop files on XDA thread.

## Credits

• @topjohnwu for magisk and magiskboot used here for its easy-to-use hexpatcher

## Source code

[Github](https://github.com/Magisk-Modules-Repo/BluetoothLibraryPatcher)

## Support

[XDA](https://forum.xda-developers.com/galaxy-note-9/development/zip-libbluetooth-patcher-fix-losing-t4017735)

## Changelog

### v1.0

- Initial release

### v1.1

- Add verification point, to know if we successfully hexpatch

### v1.2

- Add recovery installation support

### v1.3

- Modify hexpatch (more safer patch)

### v1.4

- Add support for chinese variants

### v1.5

- Check we try to apply the patch on a Samsung device & add missing chinese Note10+ 5G variant

### v1.6

- Fix brand and model detection for magisk manager and recovery installation

### v1.7

- Add support for chinese/global snapdragon on Pie
- Add support for chinese/global S/N9 snapdragon on Q & simplify the hexpatch

### v1.8

- Add support for A6, A10, A80, some S10e and N10 variants
- Apply the only known qcom fix to all of them
- Add some checks to avoid false negatives
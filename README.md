# OZO Audio Capture Redmi K40 Magisk Module

## DISCLAIMER
- OZO Audio Capture blobs are owned by Nokia™.
- The MIT license specified here is for the Magisk Module only, not for OZO Audio Capture blobs.

## Descriptions
- Audio quality enhancement for audio/video recordings ported from Xiaomi Redmi K40 (alioth) and integrated as a Magisk Module for all supported and rooted devices with Magisk
- Pre process type sound effect
- There is no user interface

## Changelog

v1.3
- Support NoMount metamodule
- Resets module folders/files permissions at post-fs-data
- Move _uninstall.log to /data/adb/logs/

v1.2
- Fix wrong target in latest KernelSU

v1.1-R2
- Tidy up aml.sh
- Exclude \*audio\*effects\*haptic\*.xml
- Fix wrong file permissions in some ROMs
- Remove unneeded files

v1.0
- Improve /odm and /my_product support detection

v0.9
- Fix architecture detection in some weird ROMs
- Fix bug in uninstall.sh

v0.8
- Allow installation in Android Emulator

v0.7
- Improve \*audio\*effects\*.xml patch detection

v0.6
- Fix conflict with modules_update while installing via recovery if Magisk installed

v0.5
- Redirect /sdcard to /data/media/"$UID"
- Add optional debug.log=1 for more detailed install log
- Kitsune Mask detection
- Restarts android.hardware.audio@4.0-service-mediatek

v0.4
- Sets ro.audio.ignore_effects to false
- Move uninstall log to /data/media/0/..._uninstall.log

## Sources
- https://dumps.tadiphone.dev/dumps/redmi/alioth qssi-user-12-SKQ1.211006.001-V13.0.3.0.SKHEUXM-release-keys
- ozosdk.license: https://github.com/something6969/vendor_nokia_TheThing

## Screenshots
https://t.me/androidryukimodsdiscussions/113355

## Requirements
- arm64-v8a or armeabi-v7a architecture
- HIDL audio service
- Magisk or Kitsune Mask or KernelSU or Apatch installed

## Installation Guide & Download Link
- Install this module https://devuploads.com/waz37ge9ekyb via Magisk app or Kitsune Mask app or KernelSU app or Apatch app or Recovery if Magisk or Kitsune Mask installed
- Install AML Magisk Module https://t.me/ryukinotes/34 only if using any other else audio mod module
- Reboot

## Optionals
- Global: https://t.me/ryukinotes/35
- Stream: https://t.me/ryukinotes/52

## Troubleshootings
Global: https://t.me/ryukinotes/34

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- https://t.me/viperatmos
- https://t.me/androidryukimodsdiscussions
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Sponsors
https://t.me/ryukinotes/25



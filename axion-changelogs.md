## v1.3 Nightly 27/05/2025
- Remove unused blobs
- Setup ELF checks and regen vendor after enabling ELF checks
- Do not manually build dependencies
- Libraries are now automatically added to PRODUCT_PACKAGES
- Patch libwfdservice to resolve duplicate dependencies
- Build libqti_vndfwk_detect.vendor:32
- Add libwfdservice_shim for WFD
- parts: Move thermal profiles to system category
- Don't declare BOARD_VENDOR

## v1.2 Beta 09/04/2025
- New kernel source
- Add support for bypass charging feature
- power: Abstract android.hardware.power-ndk dependency
- sepolicy: Remove obsolete NXP NFC and eSE rules
- sepolicy: Rewrite access to BT and WiFi MAC address files
- audio: Use AOSP USB v2 audio HAL
- audio: Remove direct flag for VOIP RX
- Move to Xiaomi fingerprint AIDL
- parts: Remove unused thermal profiles
- Downgrade WFD system stack

## v1.2 Beta 24/03/2025
- device: Move no cutout overlay packages to device tree
- device: rro_overlays: Adjust status bar padding
- device: Remove Mi Sound Enhancer
- device: Added Dolby
- device: sepolicy: Address PowerHAL denials
- device: sepolicy: Address init denials
- device: sepolicy: Address CameraHAL denials
- device: Add missing FCM
- kernel: scripts/setlocalversion: Don't append -dirty in localversion

## v1.2 18/03/2025
- device: Add aperture
- device: Remove AudioFX app
- device: Change default hotspot ssid
- device: Change a default Settings.Global.DEVICE_NAME
- device: Change default bluetooth name
- device: Change default usb string
- device: Switch SystemUI overlay to RRO overlays
- device: Adjust status bar padding
- device: tetheroffload: Version 1.1
- device: parts: Implement headset scenario
- device: parts: Add dirac icons
- device: parts: Remove clear speaker summary from manifest
- device: libperfmgr-ext: Bump to android.hardware.power-V6-ndk
- kernel: UPSTREAM: HID: core: zero-initialize the report buffer
- kernel: BACKPORT: disp: msm: dsi: add null pointer check in dsi_display_dev_remove
- kernel: qcacld-5.0: Fix the possible OOB write in country IE unpack
- kernel: arm64: configs: Enable Block IO Controller

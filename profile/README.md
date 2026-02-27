## Development for Nothing Phone (2a) "`Pacman`" and for Phone (2a) Plus "`PacmanPro`"

<div>
  <img align="right" width="35%" src="https://www.bouyguestelecom.fr/media/catalog/product/n/o/nothing-phone-2a-plus-argent-dos.png">
</div>

This organization contains all the important repositories required to build custom ROMs for Nothing Phone (2a) and Phone (2a) Plus

### Required device specific repositories
* [**Device tree**](https://github.com/Nothing-2A/android_device_nothing_Aerodactyl) (`android_device_nothing_Aerodactyl`)
* [**Device kernel tree (Compiled outputs from kernel source)**](https://github.com/Nothing-2A/android_device_nothing_Aerodactyl-kernel) (`android_device_nothing_Aerodactyl-kernel`)
* [**Vendor tree (common)**](https://gitlab.com/nothing-2a/proprietary_vendor_nothing_Aerodactyl) (`proprietary_vendor_nothing_Aerodactyl`)
* [**Vendor tree (Pacman)**](https://gitlab.com/nothing-2a/proprietary_vendor_nothing_Pacman) (`proprietary_vendor_nothing_Pacman`)
* [**Vendor tree (PacmanPro)**](https://gitlab.com/nothing-2a/proprietary_vendor_nothing_PacmanPro) (`proprietary_vendor_nothing_PacmanPro`)

### Other required repositories
* [**MediaTek sepolicy**](https://github.com/Nothing-2A/android_device_mediatek_sepolicy_vndr) (`android_device_mediatek_sepolicy_vndr`)
* [**MediaTek hardware**](https://github.com/Nothing-2A/android_hardware_mediatek) (`android_hardware_mediatek`)
* [**ParanoidGlyph**](https://github.com/Nothing-2A/android_packages_apps_ParanoidGlyph) (`android_packages_apps_ParanoidGlyph`)
* [**GlyphAdapter**](https://github.com/Pong-Development/packages_apps_GlyphAdapter) (`android_packages_apps_GlyphAdapter`)

### Required patches
* [**Add MTK packages to whitelist**](https://github.com/Nothing-2A/android_build_soong/commit/1d9d22c82c32e207d188a406c61c3d7912ceed31) (`android_build_soong`)
* [**Add a stub of TelephonyMetrics**](https://github.com/Nothing-2A/android_hardware_lineage_compat/commit/0d01b8f5594788cb73be6e39e7ed415a30fd5879) (`android_hardware_lineage_compat`)
* [**Add 60FPS recording on Aperture**](https://github.com/Nothing-2A/android_packages_apps_Aperture/commit/a4c34aa57ed56de60f29349a1e6d20cf8160ca15) (`android_packages_apps_Aperture`)
* [**Add dither logic for MTK udfps optical**](https://github.com/Nothing-2A/android_frameworks_native/commit/7b7807349f7b66c61444e32e4a26b025932117d8) (`android_frameworks_native`)
* [**SystemUI: Reverse MediaTek udfps dimlayer changes**](https://github.com/Nothing-2A/android_frameworks_base/commit/71955520858075bfeb8b52009151ba20401f27e3) (`android_frameworks_base`)

### Optional patches (fenrir patched LK support, use at your own risk)
* [**Allow booting with fenrir patched LKs**](https://github.com/Nothing-2A/android_system_core/commit/8ff6e7a68523c3b870d8dcd5713c71ea15b43dd2) (`android_system_core`)
* [**Allow flashing images from fastbootd with fenrir patched LKs**](https://github.com/Nothing-2A/android_system_core/commit/0d5990a96c5e6a404887f5575c5d00bcbbaaef74) (`android_system_core`)

### Device kernel repositories
* [**Kernel source**](https://github.com/Nothing-2A/android_kernel_nothing_mt6886) (`android_kernel_nothing_mt6886`)
* [**External kernel modules source**](https://github.com/Nothing-2A/android_kernel_modules_nothing_mt6886) (`android_kernel_modules_nothing_mt6886`)

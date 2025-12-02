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
* [**Aperture**](https://github.com/Nothing-2A/android_packages_apps_Aperture/commit/a4c34aa57ed56de60f29349a1e6d20cf8160ca15) (`android_packages_apps_Aperture`)
* [**MediaTek changes for wpa_supplicant_8**](https://github.com/Nothing-2A/android_external_wpa_supplicant_8/commit/39200b6c7b1f9ff1c1c6a6a5e4cd08c6f526d048) (`android_external_wpa_supplicant_8`)
* [**Enable WAPI for wpa_supplicant_8**](https://github.com/Nothing-2A/android_external_wpa_supplicant_8/commit/37a6e255d9d68fb483d12db550028749b280509b) (`android_external_wpa_supplicant_8`)

### Optional patches (fenrir patched LK support, use at your own risk)
* [**Allow booting with fenrir patched LKs**](https://github.com/Nothing-2A/android_system_core/commit/8ff6e7a68523c3b870d8dcd5713c71ea15b43dd2) (`android_system_core`)
* [**Allow flashing images from fastbootd with fenrir patched LKs**](https://github.com/Nothing-2A/android_system_core/commit/0d5990a96c5e6a404887f5575c5d00bcbbaaef74) (`android_system_core`)

### Device kernel repositories
* [**Kernel source**](https://github.com/Nothing-2A/android_kernel_nothing_mt6886) (`android_kernel_nothing_mt6886`)
* [**External kernel modules source**](https://github.com/Nothing-2A/android_kernel_modules_nothing_mt6886) (`android_kernel_modules_nothing_mt6886`)

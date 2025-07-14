## Development for Nothing Phone (2a) "`Pacman`" and for Phone (2a) Plus "`PacmanPro`"

<div>
  <img align="right" width="35%" src="https://www.bouyguestelecom.fr/media/catalog/product/n/o/nothing-phone-2a-plus-argent-dos.png">
</div>

This organization contains all the important repositories required to build AOSP ROMs for Nothing Phone (2a) and Phone (2a) Plus

### Required device specific repositories
* [**Device tree**](https://github.com/Nothing-2A/android_device_nothing_Aerodactyl) (`android_device_nothing_Aerodactyl`)
* [**Device kernel tree (Compiled outputs from kernel source)**](https://github.com/Nothing-2A/android_device_nothing_Aerodactyl-kernel) (`android_device_nothing_Aerodactyl-kernel`)
* [**Vendor tree (common)**](https://github.com/Nothing-2A/proprietary_vendor_nothing_Aerodactyl) (`proprietary_vendor_nothing_Aerodactyl`)
* [**Vendor tree (Pacman)**](https://github.com/Nothing-2A/proprietary_vendor_nothing_Pacman) (`proprietary_vendor_nothing_Pacman`)
* [**Vendor tree (PacmanPro)**](https://github.com/Nothing-2A/proprietary_vendor_nothing_PacmanPro) (`proprietary_vendor_nothing_PacmanPro`)

### Other required repositories
* [**MediaTek sepolicy**](https://github.com/Nothing-2A/android_device_mediatek_sepolicy_vndr) (`android_device_mediatek_sepolicy_vndr`)
* [**MediaTek hardware**](https://github.com/Nothing-2A/android_hardware_mediatek) (`android_hardware_mediatek`)
* [**Nothing hardware**](https://github.com/Nothing-2A/android_hardware_nothing) (`android_hardware_nothing`)

### Additional required patches
* [**Soong**](https://github.com/Nothing-2A/android_build_soong/commit/86857404f7ba8e175e480d79f8bca82d8c71a9b7) (`android_build_soong`)
* [**Aperture**](https://github.com/Nothing-2A/android_packages_apps_Aperture/commit/36c9507ecf2a1a798d2e7931d9019bacc3cc6052) (`android_packages_apps_Aperture`)

### Device kernel repositories
* [**Kernel source**](https://github.com/Nothing-2A/android_kernel_nothing_mt6886) (`android_kernel_nothing_mt6886`)
* [**External kernel modules source**](https://github.com/Nothing-2A/android_kernel_modules_nothing_mt6886) (`android_kernel_modules_nothing_mt6886`)

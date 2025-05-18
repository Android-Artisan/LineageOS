# 📱 LineageOS for Samsung Galaxy S20 Series (SM-G98x) / S6/E (WIP)

### ✅ Supported Devices

| Device Name       | Codename | Chipset    | Status               |
|-------------------|----------|------------|----------------------|
| Galaxy S20        | x1s      | Exynos     | [![LineageOS-x1s-WSL](https://github.com/Android-Artisan/LineageOS/actions/workflows/x1s-wsl.yml/badge.svg?event=workflow_dispatch)](https://github.com/Android-Artisan/LineageOS/actions/workflows/x1s-wsl.yml) |
| Galaxy S20        | x1q      | Snapdragon | [![LineageOS-x1q-WSL](https://github.com/Android-Artisan/LineageOS/actions/workflows/x1q-wsl.yml/badge.svg?event=workflow_dispatch)](https://github.com/Android-Artisan/LineageOS/actions/workflows/x1q-wsl.yml) |
| Galaxy S20+       | y2s      | Exynos     | [![LineageOS-y2s-WSL](https://github.com/Android-Artisan/LineageOS/actions/workflows/y2s-wsl.yml/badge.svg?event=workflow_dispatch)](https://github.com/Android-Artisan/LineageOS/actions/workflows/y2s-wsl.yml) |
| Galaxy S20+       | y2q      | Snapdragon | [![LineageOS-y2q-WSL](https://github.com/Android-Artisan/LineageOS/actions/workflows/y2q-wsl.yml/badge.svg?event=workflow_dispatch)](https://github.com/Android-Artisan/LineageOS/actions/workflows/y2q-wsl.yml) |
| Galaxy S20 Ultra  | z3s      | Exynos     | [![LineageOS-z3s-WSL](https://github.com/Android-Artisan/LineageOS/actions/workflows/z3s-wsl.yml/badge.svg?event=workflow_dispatch)](https://github.com/Android-Artisan/LineageOS/actions/workflows/z3s-wsl.yml) |
| Galaxy S20 Ultra  | z3q      | Snapdragon | [![LineageOS-z3q-WSL](https://github.com/Android-Artisan/LineageOS/actions/workflows/z3q-wsl.yml/badge.svg?event=workflow_dispatch)](https://github.com/Android-Artisan/LineageOS/actions/workflows/z3q-wsl.yml) |

### 🛠️ Status

| Component           | Status                   |
|---------------------|--------------------------|
| Boots               | ✅ Yes                   |
| Wi-Fi               | ✅ Working               |
| RIL (Calls, SMS)    | ✅ Working               |
| Mobile Data         | ✅ Working               |
| Audio               | ✅ Working               |
| Bluetooth           | ✅ Working (not in calls)|
| NFC                 | ✅ Working               |
| GPS                 | ✅ Working               |
| Camera              | ✅ Working               |
| Fingerprint         | ✅ Working               |
| VoLTE / VoWiFi      | ❌ Not Working           |

### 📦 Sources

#### 📁 Room Service
- For S20 Series Exynos [Ronnz98](https://github.com/Ronnz98)
- For S20 Series Snapdragon [Android-Artisan](https://github.com/Android-Artisan)

#### 📂 Device Trees
- [android_device_samsung_x1s](https://github.com/Ronnz98/android_device_samsung_x1s)
- [android_device_samsung_x1q](https://github.com/ArtisanROM/android_device_samsung_x1q)
- [android_device_samsung_y2s](https://github.com/Ronnz98/android_device_samsung_y2s)
- [android_device_samsung_y2q](https://github.com/ArtisanROM/android_device_samsung_y2q)
- [android_device_samsung_z3s](https://github.com/Ronnz98/android_device_samsung_z3s)
- [android_device_samsung_z3q](https://github.com/ArtisanROM/android_device_samsung_z3q)

#### 🧬 Kernel
- [android_kernel_samsung_universal9830](https://github.com/fcuzzocrea/android_kernel_samsung_universal9830)
- [android_kernel_samsung_sm8250](https://github.com/ArtisanROM/android_kernel_samsung_sm8250)

#### 🔧 Vendor Blobs
- [proprietary_vendor_samsung_snapdragon](https://github.com/ArtisanROM/proprietary_vendor_samsung)
- [proprietary_vendor_samsung_x1s](https://github.com/Ronnz98/proprietary_vendor_samsung_x1s)
- [proprietary_vendor_samsung_y2s](https://github.com/Ronnz98/proprietary_vendor_samsung_y2s)
- [proprietary_vendor_samsung_z3s](https://github.com/Ronnz98/proprietary_vendor_samsung_z3s)

#### 📚 Common Dependencies
- [openmax](https://github.com/LineageOS/android_hardware_samsung_slsi-linaro_openmax)
- [config](https://github.com/LineageOS/android_hardware_samsung_slsi-linaro_config)
- [graphics](https://github.com/LineageOS/android_hardware_samsung_slsi-linaro_graphics)
- [interfaces](https://github.com/LineageOS/android_hardware_samsung_slsi-linaro_interfaces)
- [exynos](https://github.com/LineageOS/android_hardware_samsung_slsi-linaro_exynos)
- [exynos5](https://github.com/LineageOS/android_hardware_samsung_slsi-linaro_exynos5)
- [android_hardware_samsung](https://github.com/Ronnz98/android_hardware_samsung)
- [sepolicy](https://github.com/Ronnz98/android_device_samsung_slsi_sepolicy)

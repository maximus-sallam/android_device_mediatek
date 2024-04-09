# android_device_mediatek

Dedicated to providing device-specific configurations and support for various MediaTek chipsets under the LineageOS 21.0 platform. Includes a structured directory layout housing build scripts, common device configurations, platform-specific settings, and security policies for a range of MediaTek SoCs including mt6735, mt6739, mt6755, and mt6763. Each chipset directory contains critical components such as audio configurations, sensor setups, thermal management settings, and more, tailored to ensure optimal performance and compatibility of LineageOS on devices powered by these MediaTek processors.

This repository is organized into several key directories:

- build/: Contains build-related scripts and configurations to support the compilation process.
- common/: Hosts shared resources and configurations applicable across multiple MediaTek devices.
- config/: Includes network and IMS configurations, among others, crucial for device functionality.
- mt6735/, mt6739/, mt6755/, mt6763/: Each directory is dedicated to specific MediaTek SoC models, containing device-specific makefiles, initialization scripts, and configurations for audio, sensors, thermal management, and more.
- sepolicy/ and sepolicy_vndr/: Define SELinux policies for platform and vendor-specific security enhancements.

This repository serves as a resource for developers working on integrating LineageOS with MediaTek-based devices, offering a foundation for customization, optimization, and enhancement of the OS's functionality on these chipsets.

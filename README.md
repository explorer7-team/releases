# explorer7 releases have [moved](https://github.com/explorer7-foundation/source/releases).
---
## DO NOT LINK DIRECTLY TO THIS REPO! PLEASE USE THE WINCLASSIC POST LINK AT THE START OF THIS README.
## explorer7 - ex7forw8, modernized
READ THE WINCLASSIC POST IF YOU CAME HERE FROM AN EXTERNAL LINK: https://winclassic.net/thread/3005/explorer7-restoring-windows-7-experience

This is the official repository for explorer7 releases.

Discord server: https://discord.gg/d3yVmW4xgr

### Registry options

These options are located under `HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`.

| Name | Type | Description | Default Value |
| ---- | ---- | ----------- | ------------- |
| Theme | REG_SZ | Name of the theme file to use. This is relative to the installation directory. For example, `"aero"` will use the theme at `"explorer7\theme\aero.msstyles"`, `"Aero\aero"` will use the theme at `"explorer7\theme\Aero\aero.msstyles"`. If this is not specified, `aero` will be used. | **aero** |
| OrbDirectory | REG_SZ | Name of the orb images directory to use. This is relative to the installation directory. For example, `"6801"` will use the orb images located at `"explorer7\orbs\6801\"`, `"Orb1\6801"` will use the orbs located at `"explorer7\orbs\Orb1\6801\"`. If this is not specified, the internal explorer image will be used.| **default** |
| DisableComposition | REG_DWORD | When set to 1, explorer7 will act as if the Desktop Window Manager is not running. | **0** |
| ClassicTheme | REG_DWORD | When set to 1, explorer7 will use the Windows Classic theme. | **0** |
| EnableImmersive | REG_DWORD | Controls the ability to run UWP applications in the system. When set to 0, UWP applications will not be able to run. | **0** |
| StoreAppsInStart | REG_DWORD | When set to 0, UWP applications will be hidden from the All Programs list. | **1** |
| StoreAppsOnTaskbar | REG_DWORD | When set to 0, specializations applied to load UWP application icons will not be applied. | **0 (when EnableImmersive = 0)**, **1 (when EnableImmersive = 1)** |
| ColorizationOptions | REG_DWORD | Controls shell colorization behaviour. Options 1 to 4 may have varying compatibility across Windows versions. | **1** |
| AcrylicColorization | REG_DWORD | Controls acrylic colorization behaviour. Options 0-2 control the use of immersive colours, option 3 will use the regular colorization. | **0** |
| OverrideAlpha | REG_DWORD | When set to 1, colorization alpha specified by DWM is overridden on the taskbar, start menu, and thumbnails. | **0** |
| AlphaValue | REG_DWORD | For use alongside OverrideAlpha, to specify a 2-digit hex code for the colorization system to use. | **0x6B** |
| UseTaskbarPinning | REG_DWORD | Determines whether taskbar pinning functionality is available to the user. When set to 0, pins will not be loaded and cannot be modified from jumplists. | **1** |

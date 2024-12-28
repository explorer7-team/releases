# DO NOT LINK DIRECTLY TO THIS REPO! PLEASE USE THE WINCLASSIC POST LINK AT THE START OF THIS README.
# explorer7 - ex7forw8, modernized
READ THE WINCLASSIC POST IF YOU CAME HERE FROM AN EXTERNAL LINK: https://winclassic.net/thread/2588/explorer7-windows-explorer-10-11

This is the official repository for explorer7 releases.\
DO NOT USE THIS REPO TO REPORT ISSUES. (you can't either way)

Discord Server: https://discord.gg/d3yVmW4xgr

## Registry keys

These keys are located under `HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`.

| Name | Type | Description | Default Value |
| ---- | ---- | ----------- | ------------- |
| Theme | REG_SZ | Name of the theme file to use. This is relative to the installation directory. For example, `"aero"` will use the theme at `"explorer7\theme\aero.msstyles"`, `"Aero\aero"` will use the theme at `"explorer7\theme\Aero\aero.msstyles"`. If this is not specified, `aero` will be used. | **aero** |
| OrbDirectory | REG_SZ | Name of the orb images directory to use. This is relative to the installation directory. For example, `"6801"` will use the orb images located at `"explorer7\orbs\6801\"`, `"Orb1\6801"` will use the orbs located at `"explorer7\orbs\Orb1\6801\"`. If this is not specified, the internal explorer image will be used.| **default** |
| DisableComposition | REG_DWORD | When set to 1, Explorer7 will act as if the Desktop Window Manager is not running. | **0** |
| ClassicTheme | REG_DWORD | When set to 1, Explorer7 will use the Windows Classic theme. | **0** |
| EnableImmersive | REG_DWORD | Controls the ability to run UWP apps in the system. When set to 0, UWP apps won't run. | **0** |
| EnableUWPAppsInStart | REG_DWORD | When set to 0, UWP apps will be hidden from the All Programs list. | **1** |
| ColorizationOptions | REG_DWORD | Controls shell colorization behaviour. Options 1 to 4 may have varying compatibility across Windows versions. | **1** |
| RPEnabled | REG_DWORD | When set to 1, relevant theme classes suffixed with the number "8" will be used, allowing Windows 8-based themes to render correctly. | **0** |


# Mine Launcher — Android project (v0.1.2)

Original Mine Launcher Android project starter with custom red/black/silver ML logo, Android launcher icons, and responsive UI prototype.

## Screens
Home, Versions, Mods, Resource Packs, Shaders, News, Online, Performance and Settings.

## Current functionality
- Android app shell opens a local Mine Launcher interface.
- Navigation between launcher sections works.
- Version and mod catalogues are demonstration data.
- Custom ML logo is used in the interface and Android app icon.

## Not yet functional
This is not yet a complete Minecraft launcher. Minecraft Java engine, Microsoft authentication, version and asset downloads, Java runtime management, native renderer/LWJGL integration, real mod installation, live news feed and multiplayer backend are not included yet.

## RXLauncher source audit
The supplied RXLauncher archive references `app_pojavlauncher`, `arc_dns_injector` and `forge_installer` modules but does not contain those directories. Only the `jre_lwjgl3glfw` module and project metadata/assets are present. See `SOURCE_AUDIT.md`.

If RXLauncher/Pojav-derived code is integrated later, retain applicable license notices, provide required corresponding source, and preserve attribution. See `THIRD_PARTY_LICENSES/`.

# Elenchos -- releases

Installers only. Source code lives in a separate, private repository.

| Version | Windows | macOS |
|---|---|---|
| 1.0.3 | [ElenchosSetup.exe](v1.0.3/ElenchosSetup.exe) | [Elenchos.dmg](v1.0.3/Elenchos.dmg) (pending) |

macOS build: ad-hoc signed, not notarized. Gatekeeper will block the first
launch -- right-click > Open, or:

    xattr -dr com.apple.quarantine /Applications/Elenchos.app

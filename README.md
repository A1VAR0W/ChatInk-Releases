# ChatInk Releases

Este repositorio público contiene exclusivamente binarios oficiales y metadatos de actualización de **ChatInk**. El código fuente, la infraestructura y la configuración privada no se distribuyen aquí.

## Versión actual

La versión estable actual es [v0.1.5](https://github.com/A1VAR0W/ChatInk-Releases/releases/tag/v0.1.5).

## Descargas

- [Android APK](https://github.com/A1VAR0W/ChatInk-Releases/releases/download/v0.1.5/ChatInk-0.1.5.apk)
- [iOS IPA para SideStore/AltStore](https://github.com/A1VAR0W/ChatInk-Releases/releases/download/v0.1.5/ChatInk-0.1.5.ipa)
- [SHA256SUMS](https://github.com/A1VAR0W/ChatInk-Releases/releases/download/v0.1.5/SHA256SUMS)

## Verificación

Descarga `SHA256SUMS` de la misma release y comprueba los hashes antes de instalar. En PowerShell:

```powershell
Get-FileHash .\ChatInk-X.Y.Z.apk -Algorithm SHA256
Get-FileHash .\ChatInk-X.Y.Z.ipa -Algorithm SHA256
```

## Instalación Android

Descarga únicamente el APK de la release oficial y comprueba su SHA-256 antes de instalarlo. Android puede solicitar autorización para instalar desde esa fuente; ChatInk no instala binarios de forma silenciosa.

## iOS SideStore / AltStore

La fuente compatible con SideStore y AltStore está disponible en:

```text
https://raw.githubusercontent.com/A1VAR0W/ChatInk-Releases/main/sidestore-source.json
```

Los binarios de iOS se redistribuyen para que SideStore o AltStore los firmen con la cuenta Apple del usuario. No es una distribución de App Store ni una instalación directa desde Safari.

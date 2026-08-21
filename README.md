# ChatInk Releases

Este repositorio público contiene exclusivamente binarios oficiales, sus hashes y metadatos de actualización de **ChatInk**. No contiene código fuente, configuración del servidor, certificados, keystores, tokens ni archivos de entorno.

## Estado actual

Todavía no hay una versión pública publicada. El manifiesto [latest.json](latest.json) usa `release: null` hasta que una release estable esté disponible.

## Instalación Android

1. Descarga únicamente el APK de una GitHub Release de este repositorio.
2. Descarga `SHA256SUMS` de la misma release y verifica el hash antes de instalar.
3. Abre el APK. Android puede pedir autorización para instalar desde esa fuente.

ChatInk no descarga ni instala APKs en segundo plano.

```powershell
Get-FileHash .\ChatInk-X.Y.Z.apk -Algorithm SHA256
```

## iOS: SideStore / AltStore

Las versiones iOS se distribuyen como IPA para que SideStore o AltStore las firmen con la cuenta Apple del usuario. No son una instalación directa desde Safari ni una publicación de App Store.

Añade esta fuente en SideStore o AltStore cuando exista la primera release:

```text
https://raw.githubusercontent.com/A1VAR0W/ChatInk-Releases/main/sidestore-source.json
```

## Contenido permitido

La rama `main` solo contiene `README.md`, `latest.json`, `sidestore-source.json` e `icon-512.png`. Los APK, IPA y `SHA256SUMS` se publican exclusivamente como assets de GitHub Releases.

# Firmware releases

Public firmware packages and update catalogs for compatible devices.
Application source and development records are maintained separately.

## Solar display

ESP32-S3 energy display: 16 MiB flash, 8 MiB OPI PSRAM, 480 × 480 RGB panel and GT911 touch.
Use firmware only on compatible hardware.

- Stable catalog: [`solar-display/stable.json`](solar-display/stable.json)
- Release tags: `solar-display-vX.Y.Z`
- Download `firmware.solarota` from the chosen release for a local web update.
- `firmware.json` describes the embedded version, hardware and SHA-256.

Installation requires explicit confirmation. Browser installations additionally require
opening the ten-minute permission window on the display. Device settings are stored
separately from application firmware. Individual network passwords and device backups
are not distributed here. The display needs no GitHub token to read these public files.

Each project has its own catalog; the repository-wide latest release is not an update selector.
Tags identify distributed binaries. GitHub's automatically generated source archives contain
only this distribution repository, not the application source.

Third-party components retain their respective licenses; see [notices](THIRD_PARTY_NOTICES.md).

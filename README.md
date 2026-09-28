# Minecraft Version Index

All Minecraft version JSONs hosted on GitHub for GlassLauncher.

## Structure

- `version-index.json` — индекс всех версий (ID, тип, время, ссылка на JSON)
- `version_manifest.json` — оригинальный manifest от Mojang
- `*.json` — version JSON для каждой версии (например, `1.21.4.json`, `1.20.1.json`)

## Usage

GlassLauncher загружает `version-index.json` и использует его для сканирования доступных версий.
Каждая версия хранится как отдельный файл `{id}.json`.

## Sources

- Mojang: `https://launchermeta.mojang.com/mc/game/version_manifest.json`
- Legacy Launcher: `~/.tlauncher/legacy/Minecraft`

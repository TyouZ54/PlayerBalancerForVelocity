# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [2.4.0] - 2026-10-13

### Changed
- Bump project version to 2.4.0
- Target Velocity API 3.4.0 (was 3.2.0-SNAPSHOT)
- Compile with Java 17
- Replace deprecated `JsonParser` constructor usage with `JsonParser.parseString`
- Disable remote update checker (upstream project is archived)
- Point SCM / issue tracker to this repository
- Bump maven-shade-plugin to 3.5.3 (fixes shade on modern JDKs)
- Config header cleaned for Velocity fork

### Notes
- Fork of [BGHDDevelopment/PlayerBalancer](https://github.com/BGHDDevelopment/PlayerBalancer) focused on Velocity.
- BungeeCord / Spigot addon modules are still present but not the primary target.

## [2.3.6] - 2024-07-09

### Upstream
- Last release from BGHDDevelopment/PlayerBalancer (archived).

# DeluxeHub 26.2 update

This package updates the supplied DeluxeHub 3.5.2 source to DeluxeHub 3.8.5,
the current upstream release published for Minecraft 26.2.

## Included

- `DeluxeHub-3.8.5.jar`: ready-to-install plugin artifact.
- Updated Java source and Gradle build files.
- Modernized dependencies, including XSeries, FoliaLib, and Item-NBT-API 2.16.0.
- Java 21 toolchain configuration for building the source.
- Folia support and fixes from the current upstream release.

## Install

1. Stop the server.
2. Back up the existing `plugins/DeluxeHub` folder.
3. Replace the old DeluxeHub jar with `DeluxeHub-3.8.5.jar`.
4. Start the server on a Paper, Spigot, or Folia 26.2-compatible build.

The plugin keeps its normal `DeluxeHub` plugin name. Its implementation package
is now `net.zithium.deluxehub`, so remove the old jar rather than running both
versions at the same time.

## Build from source

Use JDK 21 or newer:

```text
./gradlew build
```

The resulting jar is written to `build/libs/DeluxeHub-3.8.5.jar`.
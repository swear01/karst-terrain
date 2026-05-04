# Karst Terrain

NeoForge 1.21.1 mod that adds a Karst Highlands biome to the Overworld.

## Content

- `karst_terrain:limestone`
- `karst_terrain:weathered_limestone`
- Creative tab: `Karst Terrain`
- `karst_terrain:karst_highlands` Overworld biome
- TerraBlender integration for Overworld biome placement

## World Generation

Karst Terrain adds `karst_terrain:karst_highlands` as a new Overworld biome. It is placed in mountain-like inland climate slots via TerraBlender, so vanilla biomes are not directly modified.

Generated features:

- limestone strata replacing stone underground and in exposed mountain stone
- weathered limestone pockets near higher terrain

Locate it with:

```mcfunction
/locate biome karst_terrain:karst_highlands
```

## Build

```bash
./gradlew build
```

The built jar is written to:

```text
build/libs/karst_terrain-0.1.0.jar
```

## Test Runs

```bash
./gradlew runClient
./gradlew runServer
./gradlew runData
```

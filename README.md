# Tribaldustry
Tribal Stage of Mindustry

## Compiling
JDK 8.\
Task `dexify` requires `d8` from Android `build-tools` > `28.0.1`.

Plain Jar is for JVMs (desktop).\
Dexed Jar is for for JVMs (desktop) and ARTs (Android).\
These two are separate in order to decrease size of mod download.

### Windows
Plain Jar: `gradlew build`\
Dexify Plain Jar: `gradlew dexify`\
Build Plain & Dexify Jar: `gradlew buildDex`

### *nix
Plain Jar: `./gradlew build`\
Dexify Plain Jar: `./gradlew dexify`\
Build Plain & Dexify Jar: `./gradlew buildDex`

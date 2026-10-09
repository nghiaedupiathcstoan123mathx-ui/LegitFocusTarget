# LegitFocusTarget — Minecraft 1.21.11

Client-side Fabric mod project. Java 21 is required.

## Build locally

If you have Gradle installed:

```bash
gradle --no-daemon build
```

The compiled mod JAR is written to `build/libs/`.

## Build automatically on GitHub

This repository includes `.github/workflows/build.yml`. Push the project to GitHub, then open **Actions → Build LegitFocusTarget**. When the workflow completes, open its run and download the artifact named `LegitFocusTarget-Minecraft-1.21.11`.

The workflow installs Gradle directly, so `gradlew` and `gradle/wrapper/` are not required. The artifact is a build output, not a guarantee of compatibility with every Lunar Client release. Test it in a separate instance first.

# Dockerized Android APK builder

Quickly and easily build Android APKs from docker

Contains Gradle and Android SDK

## Usage

```sh
docker run --rm --volume $(pwd):/app/ -w /app ghcr.io/zetier/android_apk_builder:latest gradle build
```

## Tags

Tags will be formatted as `gradle-<GRADLE_VERS>-sdk-<SDK_VERS>`

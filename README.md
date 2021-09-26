# lavaplayer-natives

[![lavaplayer version](https://img.shields.io/maven-metadata/v?label=lavaplayer&metadataUrl=https%3A%2F%2Fm2.dv8tion.net%2Freleases%2Fcom%2Fsedmelluq%2Flavaplayer%2Fmaven-metadata.xml&style=for-the-badge)](https://github.com/sedmelluq/lavaplayer)
[![lavaplayer version](https://img.shields.io/maven-metadata/v?label=lavaplayer-natives&metadataUrl=https%3A%2F%2Fm2.dv8tion.net%2Freleases%2Fcom%2Fsedmelluq%2Flavaplayer-natives%2Fmaven-metadata.xml&style=for-the-badge)](https://github.com/sedmelluq/lavaplayer-natives)
[![lavaplayer version](https://img.shields.io/maven-metadata/v?label=lavaplayer-natives-aarch64&metadataUrl=https%3A%2F%2Fmaven.masterzach32.net%2Fartifactory%2Flibraries%2Fcom%2Fsedmelluq%2Flavaplayer-natives-aarch64%2Fmaven-metadata.xml&style=for-the-badge)](https://maven.masterzach32.net/ui/repos/tree/General/libraries%2Fcom%2Fsedmelluq%2Flavaplayer-natives-aarch64)

Native libraries for Lavaplayer

This repo adds support for building aarch64 binaries

An example
`build.gradle.kts`:
```kotlin
repositories {
    maven("https://maven.masterzach32.net/artifactory/libraries")
}

dependencies {
    implementation("com.sedmelluq:lavaplayer:1.3.78")
    runtimeOnly("com.sedmelluq:lavaplayer-natives-aarch64:1.3.14")
}
```

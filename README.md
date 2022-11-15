# Gradle GraalVM skeleton

Serves as a starting point for a GraalVM native-image application built with Gradle.

## How to use

Download [the ZIP file](https://github.com/mhalbritter/gradle-graalvm-skeleton/archive/refs/heads/main.zip), extract it
somewhere and start hacking.

## Building a native-image

```shell
./gradlew nativeCompile
```

The native image is written to `build/native/nativeCompile/gradle-graalvm-skeleton`.

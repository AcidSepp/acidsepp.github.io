---
layout: post
title:  "Programmieren II on Windows"
---

## Install JDK 25

Install Java:

```powershell
winget install EclipseAdoptium.Temurin.25.JDK
```

Verify the installation, make sure that the version is "25" and the name contains "OpenJDK Runtime Environment Temurin":

```powershell
java -version
```
The output should look like this:

```powershell
openjdk version "25" 2025-09-16 LTS
OpenJDK Runtime Environment Temurin-25+36 (build 25+36-LTS)
OpenJDK 64-Bit Server VM Temurin-25+36 (build 25+36-LTS, mixed mode, sharing)
```

## Install Gradle

Install [Gradle](https://docs.gradle.org/current/userguide/installation.html#ex-installing-manually)

Verify the installation, make sure that the version is "9":

```powershell
gradle -version
```

## Install IntelliJ

Install the [JetBrains Toolbox](https://www.jetbrains.com/toolbox-app/)

Open the JetBrains Toolbox widget and click "install" on "IntelliJ Idea Community Edition".


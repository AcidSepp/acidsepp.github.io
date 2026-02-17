---
layout: post
title:  "Programmieren II on Linux"
---

## Prerequisites

Install [sdkman](https://sdkman.io/)

## Install JDK 25

Install Java:

```bash
sdk install java 25-tem
```

Verify the installation, make sure that the version is "25" and the name contains "OpenJDK Runtime Environment Temurin":

```bash
java -version
```
The output should look like this:

```bash
openjdk version "25" 2025-09-16 LTS
OpenJDK Runtime Environment Temurin-25+36 (build 25+36-LTS)
OpenJDK 64-Bit Server VM Temurin-25+36 (build 25+36-LTS, mixed mode, sharing)
```

## Install Gradle

Install Gradle:

```bash
sdk install gradle 9.3.1
```

Verify the installation, make sure that the version is "9":

```bash
gradle -version
```

## Install IntelliJ

Install the [JetBrains Toolbox](https://www.jetbrains.com/help/toolbox-app/toolbox-app-silent-installation.html#toolbox_linux)

Open the JetBrains Toolbox widget and click "install" on "IntelliJ Idea Community Edition".
---
layout: post
title:  "Programmieren II on MacOs"
---

## Prerequisites

Install [homebrew](https://brew.sh/)

## Install JDK 25

Install Java:

```zsh
brew install --cask temurin@25
```

Verify the installation, make sure that the version is "25" and the name contains "OpenJDK Runtime Environment Temurin":

```zsh
java -version
```
The output should look like this:

```zsh
openjdk version "25" 2025-09-16 LTS
OpenJDK Runtime Environment Temurin-25+36 (build 25+36-LTS)
OpenJDK 64-Bit Server VM Temurin-25+36 (build 25+36-LTS, mixed mode, sharing)
```

## Install Gradle

Install Gradle:

```zsh
brew install --cask gradle@9
```

Verify the installation, make sure that the version is "9":

```zsh
gradle -version
```

## Install IntelliJ

Install the JetBrains Toolbox:
```zsh
brew install --cask jetbrains-toolbox
```

Open the JetBrains Toolbox widget and click "install" on "IntelliJ Idea Community Edition".


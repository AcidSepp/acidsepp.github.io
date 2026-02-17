---
layout: post
title:  "Programmieren II on Windows"
---

## Install JDK 25

- Open PowerShell as administrator to install Java:

```powershell
winget install EclipseAdoptium.Temurin.25.JDK
```

- Restart PowerShell
- Verify the installation, make sure that the version is "25" and the name contains "OpenJDK Runtime Environment Temurin":

```powershell
java -version
```
- The output should look like this:

```powershell
openjdk version "25" 2025-09-16 LTS
OpenJDK Runtime Environment Temurin-25+36 (build 25+36-LTS)
OpenJDK 64-Bit Server VM Temurin-25+36 (build 25+36-LTS, mixed mode, sharing)
```

## Install Gradle

- Install [Gradle](https://docs.gradle.org/current/userguide/installation.html#ex-installing-manually)
- Restart PowerShell
- Verify the installation, make sure that the version is "9":

```powershell
gradle -version
```
- The output should look like this:

```powershell
------------------------------------------------------------
Gradle 9.3.1
------------------------------------------------------------
```

## Install IntelliJ

- Install the [JetBrains Toolbox](https://www.jetbrains.com/toolbox-app/)
- Open JetBrains Toolbox and click "install" on "IntelliJ IDEA".
- Open IntelliJ and create a new Java project:
  - Name: test
  - Location: "~\IdeaProjects"
  - Build system: Gradle
  - JDK: Eclipse Temurin 25
  - Gradle DSL: Kotlin
  - Add Sample Code: yes
  
[](windowsProject.png)

- In your project open "src/main/java/org.example/Main.java"
- Press the green play button next to the main method and verify that everything works correctly
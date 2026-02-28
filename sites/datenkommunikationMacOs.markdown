---
layout: post
title:  "Datenkommunikation on MacOs"
---

{% include_relative basicSetupMacOs.markdown %}

## Docker

- Install Docker:

```bash
brew install --cask docker-desktop
```

- Verify the installation:

```bash
docker -v
```
- The output should look like this:

```bash
Docker version 29.2.1, build a5c7197
```

## Command Line Tools

- Install the `nc` command:

```zsh
brew install netcat
```
- Verify the installation:

```bash
nc -h
```
- The output should look like this:

```zsh
OpenBSD netcat (Debian patchlevel 1.229-1build1)
```

- Check, if the `dig` command is installed:

```zsh
dig -vDiG 9.20.11-1ubuntu2.1-Ubuntu
```

- The output should look like this:

```zsh
DiG 9.20.11-1ubuntu2.1-Ubuntu
```
- If `dig` is not installed, install it:

```zsh
brew install bind
```

## Wireshark

- Install Wireshark:

```bash
brew install wireshark
```

- Verify the installation:

```bash
wireshark --version
```

- The output should look like this:

```bash
Wireshark 4.6.3.
```


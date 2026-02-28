---
layout: post
title:  "Datenkommunikation on MacOs"
---

{% include_relative basicSetupMacOs.md %}

{% include_relative dockerMacOs.md %}

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

{% include_relative wiresharkMacOs.md %}


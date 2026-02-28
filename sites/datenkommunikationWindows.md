---
layout: post
title:  "Datenkommunikation on Windows"
---

{% include_relative basicSetupWindows.md %}

{% include_relative dockerWindows.md %}

## Command Line Tools

- Install wsl

```powershell
wsl --install
```

- Reboot your Computer
- Install a Linux distribution:

```powershell
wsl --install Ubuntu 
```

- Enter a Linux shell

```powershell
wsl
```
- check if the `nc` command is installed

```bash
nc -h
```
- The output should look like this:

```zsh
OpenBSD netcat (Debian patchlevel 1.229-1build1)
```

- Check, if the `dig` command is installed:

```bash
dig -vDiG 9.20.11-1ubuntu2.1-Ubuntu
```

- The output should look like this:

```bash
DiG 9.20.11-1ubuntu2.1-Ubuntu
```

- Check, if the `nslookup` command is installed:

```bash
nslookup tcpbin.com
```

{% include_relative wiresharkWindows.md %}
---
layout: post
title:  "Datenkommunikation on Windows"
---

{% include_relative basicSetupWindows.markdown %}

## Docker

- Install docker

```
winget install --id=Docker.DockerDesktop -e
```
- Restart PowerShell
- Verify the installation:

```
docker -v
```

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

## Wireshark

- Install Wireshark

```powershell
winget install --id=WiresharkFoundation.Wireshark -e
```

- Install [Npcap](https://npcap.com/#download)

---
layout: post
title:  "Datenkommunikation on Linux"
---

{% include_relative basicSetupLinux.markdown %}

## Docker

- Install Docker: https://docs.docker.com/engine/install/
- Verify the installation

```bash
docker -v
```
- The output should look like this:

```bash
Docker version 29.2.1, build a5c7197
```

## Wireshark

- Install Wireshark:

```bash
sudo add-apt-repository ppa:wireshark-dev/stable
sudo apt update
sudo apt install wireshark
```

- Verify the installation:

```bash
wireshark --version
```

- The output should look like this:

```bash
Wireshark 4.6.3.
```
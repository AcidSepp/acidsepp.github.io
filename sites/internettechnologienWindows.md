---
layout: post
title:  "Internettechnologien on Windows"
---

{% include_relative basicSetupWindows.md %}

{% include_relative wiresharkWindows.md %}

## Examples Repository

- Clone the examples repository (preferable in `~/IdeaProjects`):

```
git clone https://github.com/AcidSepp/internettechnologien-examples.git
```

- Place the slides you download from moodle in the `slides` directory, to enable opening the examples directly from the slides.

- Start the Server:

```
./gradlew examples:bootRun`
```
---
description: Feature Overview
keywords:
- Status
- Features
title: Features
---

{{< feature >}}

# High Performance

## nyan
openage uses a rigorous Entity Component System (ECS) architecture to organize game logic. This abstracts away some of the parallelism work, allowing easier exploitation of multi-threading in games. The ECS is rich in features and very efficient, as it never does any memory locking while remaining entirely thread-safe.

TODO: custom renderer:
## Vulkan

TO ADD: eventbased simulation, modernlanguages, c++-python-interface
---
description: >-
  Sid provides (theoretically) unlimited computing resources, though it is
  worthwhile to economize and consider the necessary scale of your application.
---

# Determining Resource Requirements

## CPU

* Multi-threading
* Parallelization
* Refactoring

## RAM

Find the _**main**_ looping portion of your application, and determine the total size \(in bytes\) of all your variables.  Are you reading in chunks of data \(e.g., line-by-line, item-by-item\), or do you slurp it all in in one single go?

## Disk

* Ephemeral Storage
* Google Drive
* Azure \(coming soon\)


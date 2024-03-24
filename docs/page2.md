---
permalink: /lol
layout: post
---

# LOL page

a.k.a. "page 2"

## alerts test

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> {% octicon infinity height:24 %}
> Advises about risks or negative outcomes of certain actions.

{% include alerts/primary.html content="A primary alert" %}

{% include alerts/primary.html content="
A primary alert
```go
n.storage.ApplySnapshot(rd.Snapshot)
n.storage.SetHardState(rd.HardState)
n.storage.Append(rd.Entries)
```
" %}

---
permalink: /
---
# Test gh-pages project

## linking to docs/README.md (has 'permalink: /'):

- [docs/README.md](docs/README.md) - nope (this redirects to `https://zvold.github.io/test-gh-pages/` so stays on the same page)
- [docs/](docs/) - nope
- [docs/README.html](docs/README.html) - nope

## linking to docs/page1.md (no front matter):

- [docs/page1.md](docs/page1.md) - yep
- [docs/page1.html](docs/page1.html) - yep
- [docs/page1](docs/page1) - yep

## linking to docs/page2.md ('permalink: /lol'):

- [lol/](lol/) - nope
- [lol](lol) - yep (with `zvold.github.io/test-gh-pages/lol` URL)
- [docs/page2.md](docs/page2.md) - yep (URL as above)
- [docs/lol](docs/lol)

Running this from any location should work:

```
go run github.com/zvold/test-gh-pages/01-hello-world@latest 
```

## alerts test

{% octicon info height:24 %}

{% octicon package height:24 %}

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

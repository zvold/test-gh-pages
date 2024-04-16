# Test gh-pages project (deploying from /docs)

## docs/index.md ('permalink: /'):

- [docs/index.md](docs/index.md)
- [docs/index.html](docs/index.html)
- [https://zvold.github.io/test-gh-pages/](https://zvold.github.io/test-gh-pages/)
- [https://zvold.github.io/test-gh-pages](https://zvold.github.io/test-gh-pages)

## linking to docs/index.md ('permalink: /'):

- [docs/index.md](docs/index.md) - yep (URL `https://zvold.github.io/test-gh-pages/` ?)
- [docs/](docs/) - nope
- [/](/)
- [docs/index.html](docs/index.html) - nope

## linking to docs/page1.md (no front matter):

- [docs/page1.md](docs/page1.md) - yep
- [docs/page1.html](docs/page1.html) - yep
- [docs/page1](docs/page1) - yep

## linking to docs/page2.md ('permalink: /lol'):

- [lol/](lol/) - nope
- [lol](lol) - yep (with `zvold.github.io/test-gh-pages/lol` URL)
- [/lol/](/lol/)
- [/lol](lol)
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
> ```go
> n.storage.ApplySnapshot(rd.Snapshot)
> n.storage.SetHardState(rd.HardState)
> n.storage.Append(rd.Entries)
> ```

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## License

The documentation in the [`docs/`](docs) folder is licensed under a [CC-BY license](LICENSE).

All code in this repository is licensed under the [MIT license](LICENSE-CODE).

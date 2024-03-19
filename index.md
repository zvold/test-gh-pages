# Test gh-pages project

## linking to docs/README.md (has 'permalink: /'):

- [docs/README.md](docs/README.md) - nope
- [docs/](docs/) - nope
- [docs/README.html](docs/README.html) - nope

## linking to docs/page1.md (no front matter):

- [docs/page1.md](docs/page1.md) - yep
- [docs/page1.html](docs/page1.html) - yep
- [docs/page1](docs/page1) - yep

## linking to docs/page2.md ('permalink: /lol'):

- [lol/](lol/)
- [lol](lol)
- [docs/page2.md](docs/page2.md)
- [docs/lol](docs/lol)

Running this from any location should work:

```
go run github.com/zvold/test-gh-pages/01-hello-world@latest 
```

 

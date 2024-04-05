---
layout: default
---
# Page 1

No "front matter"

# jekyll callouts

<div class="callout callout-primary" markdown="span">
A primary callout.
</div>

<div class="callout callout-secondary" markdown="span">
A secondary callout.
```go
n.storage.ApplySnapshot(rd.Snapshot)
n.storage.SetHardState(rd.HardState)
n.storage.Append(rd.Entries)
```
</div>

## render some Go code

Some inline `code` and `identifiers`.

```go
package main

import "fmt"

func main() {
	fmt.Println("hello world!")
}
```

## link back to parent:

- [index.md](index.md) - https://zvold.github.io/test-gh-pages/
- [index.html](index.html) - same
- [/](/) - nope (https://zvold.github.io)
- [.](.) - yes, root: https://zvold.github.io/test-gh-pages/
- [..](..) - nope (https://zvold.github.io/)

## link to another page:

- [page2.md](page2.md) - https://zvold.github.io/test-gh-pages/lol
- [/page2.md](/page2.md) - same
- [/page2.html](/page2.html) - nope (https://zvold.github.io/page2.html)
- [/lol](/lol) - nope (https://zvold.github.io/lol)
- [/lol/](/lol/) - nope (https://zvold.github.io/lol/)
- [lol](lol) - https://zvold.github.io/test-gh-pages/lol
- [lol/](lol/) - nope (https://zvold.github.io/test-gh-pages/lol/)
- [/page2](/page2) 
- [/page2/](/page2/)
- [page2](page2) - nope because it's /lol (https://zvold.github.io/test-gh-pages/page2)
- [page2/](page2/)

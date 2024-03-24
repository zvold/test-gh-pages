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
</div>

## render some Go code

```go
package main

import "fmt"

func main() {
	fmt.Println("hello world!")
}
```

## link back to parent:

- [index.md](index.md)
- [index.html](index.html)
- [/](/)

## link to another page:

- [page2.md](page2.md)
- [/page2.md](/page2.md)
- [/page2.html](/page2.html)
- [/page2](/lol) - nope
- [/page2/](/lol/) - nope
- [lol](lol) - https://zvold.github.io/test-gh-pages/lol
- [lol/](lol/) - nope

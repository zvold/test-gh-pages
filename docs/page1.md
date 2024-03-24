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

- [index.md](index.md) - https://zvold.github.io/test-gh-pages/
- [index.html](index.html) - same
- [/](/) - https://zvold.github.io
- [.](.) 
- [..](..) 

## link to another page:

- [page2.md](page2.md) - https://zvold.github.io/test-gh-pages/lol
- [/page2.md](/page2.md) - same
- [/page2.html](/page2.html) - nope
- [/lol](/lol) - nope (https://zvold.github.io/lol)
- [/lol/](/lol/) - nope (https://zvold.github.io/lol/)
- [lol](lol) - https://zvold.github.io/test-gh-pages/lol
- [lol/](lol/) - nope
- [/page2](/page2) 
- [/page2/](/page2/)
- [page2](page2)
- [page2/](page2/)

### Lazy sequences working hard

- lazy sequences can be chained
- language/library support for lazy sequences 
Your programs are streams of sequences which are chained together, not a sequence of method calls.

```
M = 1000 * 1000
R = range(M)
R[666]
R[::1000] # range(0,10^6) 1000
```

- activity is deferred till required
- `map`, `filter`, `dict.keys` are all lazy
- generators offer support for lazy sequences


```
import random

def flip_a_coin():
    while True:
        yield random.choice(['Head', 'Tail'])

flip_a_coin()

heads= sum(
    1 for h, _ in zip(ht, range(100000)) if h == `Heads`
)
```

- many functions in the Python standard are generators
- python sequencing works like shell pipeline

https://github.com/JulienPalard/Pipe
You can do something like this:

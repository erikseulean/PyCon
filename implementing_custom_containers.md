#### Implementing custom containers

Deciding about choosing the optimal container(collection)


Container:

```
container: hasattr(something, '__contains__')
collection:
hasattr('__contains__', '__iter__', '__size__')
```

or

``` 
from collections.abc import Container, Collection

isinstance(object, Collection)
isinstance(object, Container)

```

`collections.namedtuple` - nicer representation of a tuple

```
Participant = namedtuple('name', 'age', 'weight')
participant = Participant('erik', 10, 100)
```

`__new__.__defaults__` - set defaults to immutable objects(by using new)

Define `__new__` for input validation on a container.


```
import collections.abc.MutableMapping

class MyMapping(MutableMapping):
   pass

my_map = MyMapping("input.csv")
for item in my_map:
    print(item)
```


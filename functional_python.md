### Functional Python - Paul Willjones

Coconut - pythonic functional language

- lazy evaluation
- pure functions 
- recursion, tail recursion
- no mutations

Fewer bugs, code easier to test, code reuse

``` 
def add(a, b):
    return a + b
def cube(x): return x * x * x

def a(x):
    def b(y):
       print(x * y)
    return b

a(2)(3) => 6 #function chaining

```

Immutability leads to Referential Transparency.
No side effects, we always know what the function will return

Immutable - complex, string, tuple


#### Immutable collections in python:

``` 
from collections import namedtuple, frozenset
```

Trampoline to debug tail recursion, as the stack is being destroyed otherwise. 


#### Lazy evaluation using generator:
``` 
def give_me_value():
   for _ in range(10):
        yield _

give_me_value()
give_me_value()
give_me_value()
```

Decorators, map, reduce, filter - also ease using python in a functional way.

Libraries for functional programming 

``` 
from functools import reduce  
import itertools
import operator
``` 
Scala style stuff: 
``` 
import fn
```

Coconut - functional programming language that compiles to python
- Can be used for pipeline style programming
- Can use python modules
- Compiles into python code (2, 3)

```
pip install funcy
pip install coconut
```
#### Resources 
```podcast.__init__ ```- podcast\
So you want to be a functional programmer ? 
Functional programming in python - Youtube
#### Making all the boring things go away

- Multiple scripts end up needing framework
- Each script is usually a single function
- Much shared config

Modularize everything to increase redability and testability.

Mush - Dependency injection framework. Like Ninject. Create method call order declaratively. 

Summary
- keep tasks and frameworks separately
- abstract and test frameworks independnently
- if you use mush use labels

mush: 
https://mush.readthedocs.io
search for `mush python`

testfixtures:
http://testfixtures.readthedocs.io

click:
http://click.pocoo,org

PyYAML - config parser
https://github.com/yaml/pyyaml

Validation:
`voluptuous`
`mushroom`
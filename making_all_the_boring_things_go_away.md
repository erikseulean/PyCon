#### Making all the boring things go away

[Presentation link](http://slides.simplistix.co.uk/PyConUK2017-boring-things)

- Multiple scripts end up needing framework
- Each script is usually a single function
- Much shared config

Modularize everything to increase redability and testability.

Mush - Dependency injection framework. Like Ninject. Create method call order declaratively. 

Summary
- keep tasks and frameworks separately
- abstract and test frameworks independnently
- if you use mush use labels

##### mush: 
https://mush.readthedocs.io\
search for `mush python`

##### testfixtures:
http://testfixtures.readthedocs.io\
search for `textfixtures python`

##### click: (command line argument parser)
http://click.pocoo.org

##### PyYAML - config parser
https://github.com/yaml/pyyaml

#### Validation:
`voluptuous` - https://pypi.python.org/pypi/voluptuous \
`mushroom` - http://marshmallow.readthedocs.io/\
This tutorial is for python developers.

## Prerequisites
- Intermediate level knowledge of Python programming language
- Basic knowledge of Telethon
- Some idea about how `tgcf` works


Writing a plugin is a piece of cake. A plugin is basically a python module that can be imported by `tgcf`. You can even package it and publish it to PyPI for providing an easy `pip install` for your users.

## Naming Conventions

The plugin name (also known as plugin id) should be a single word in lowercase describing the feature.

For example: if your plugin name is `hello`, then the name of the package should be `tgcf_hello`, and the name of the plugin class should be `TgcfHello`.

## Create a Plugin

First of all, create a folder named `tgcf_hello`, and inside it create `__init__.py`. For the sake of simplicity, in this example, we will be writing our logic inside `__init__.py`. For complex plugins, you can have multiple modules and even sub-packages.


```python
# __init__.py

from telethon.hints import MessageLike

class TgcfHello:
    id = "hello"

    def __init__(self, data):
        self.data = data
        # validate the data here

    def modify(self, message:MessageLike):
        # manipulate the message here
        return message

```

More details to be added soon!

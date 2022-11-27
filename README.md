AirBnB_clone
====

This project is to build a clone of the AirBnB website. 

## Command Line Interface
The project implements a `console`, Command-Line-Interface(CLI) to manage program data. CLI allow to input commands to create, update, and destroy objects in `file storage`.

### Usage
Clone this repository to local machine. The CLI works both in interactive mode and non-interactive mode. Execute the following command to start the CLI in interactive mode. 

```bash
$ ./console.py
```
### Commands
Command | Interactive mode | Non-Interactive mode
------- | ------- | -------
Show available commands | `(hbnb) help` | `$ echo "help" \| ./console.py`
Create an new class of given type| ```(hbnb) create <className>``` | `$ echo "create <className>" \| ./console.py`
Show an object with a given ID | ```(hbnb) show <className> <id>``` or ```(hbnb) <className>.show(<id>)``` | `$ echo "show <className> <id>" \| ./console.py`
Destroy an object with a given ID | ```(hbnb) destroy <className> <id>``` or ```(hbnb) <className>.destroy(<id>)``` | `$ echo "destroy <className> <id>" \| ./console.py`
Show all objects, or all instances of a class | ```(hbnb) all <className>``` or ```(hbnb) <className>.all()``` | `$ echo "all <className> <id>" \| ./console.py`
Update an attribute of an object | ```(hbnb) update <className> <id> <attribute_name> "<attribute_value>"``` or ```(hbnb) <className>.update(<id>, <attribute_name>, "<attribute_value>")``` | `$ echo "update <className> <id> <attribute_name> "<attribute_value>" \| ./console.py`




## Unittest
Test files found in `tests` folder.

All  files, classes, functions can be tested with the followng command.
```bash
$ python3 -m unittest discover tests
```



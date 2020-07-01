#  AirBnB clone - The console

This is a command-line interface from which you can create, modify and delete objects in your file storage.

## Execution

As simple as type ./consoly.py at the root of the project.

### Commands

```
create: Creates a new instance of BaseModel
destroy: Deletes an instance based on the class name and id
update: Updates an instance based on the class name and id
all: Prints all string representation of all instances based or not on the class name.
show: Prints the string representation of an instance based on the class name and id
```
### Examples

```
(hbnb) create BaseModel
696be159-4cb9-467f-bf4b-3e71252be501

(hbnb) all BaseModel
["[BaseModel] (2494ddab-f41b-4677-98c5-663e7711bcea) {'id': '2494ddab-f41b-4677-98c5-663e7711bcea...

(hbnb) update BaseModel 578a7d0f-5d79-476f-802c-93389d5561ee first_name "test"

(hbnb) show BaseModel 78a7d0f-5d79-476f-802c-93389d5561ee
[BaseModel] (578a7d0f-5d79-476f-802c-93389d5561e...
```

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

## Versioning

We use python 3.4

## License

Free license

## Acknowledgments

- Based on AirBnB page.

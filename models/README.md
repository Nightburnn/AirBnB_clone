# MODELS
## this is a table explaining each file in our model

| files        | short explaination |
| -------------|:-----------------:|
|base_model.py |The Basemodel provides a blueprint for creating other models in the project|
|amenity.py|Subclass of basemodel, with one attribute, name, which is an empty string that holds the name of the amenity|
|place.py|Subclass of basemodel. All the atrributes of the place class are initaialized as empty stings, 0, or 0.0 . Read Docstrings for more|
|review.py| Subclass of basemodel. represent the review and has three instances. Read Docstring for more|
|state.py| Subclass of basemodel. The class has one attribute name which is a string that represents the name of the state|
|city.py|Subclass of basemodel. The class has two class level variables,The City class also has an __init__ method which calls the parent class's __init__ method  using the super() function|
|user.py|Subclass of model.The class has four attributes, each of which is a string data type and is initialized to an empty string. These attributes represent the email, password, first name and last name of a user respectively|
|__init__.py|instance of the filestorage class and calling the reload method|


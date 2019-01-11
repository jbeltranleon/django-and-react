# Django Rest Framework and React
https://www.valentinog.com/blog/tutorial-api-django-rest-react/

* To execute coverage: `coverage run --source='.' manage.py test`
* To generage the html: `coverage html`
* To see the report in terminal: `coverage report`


> Serialization is the act of transforming an object into another data format. 

### Why serialization is necessary?
Think of a Django model: it’s a Python class. How do you render a Python class to JSON in a browser?
**With a Django REST serializer!**
A serializer works the other way around too: it converts JSON to objects.

This way you can:
* display Django models in a browser by converting them to JSON
* make CRUD request with a JSON payload to the API
> To recap: a Django REST serializer is mandatory for operating on models through the API.
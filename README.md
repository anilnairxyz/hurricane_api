# Market Loss modeling
A python (Flask) webapp boilerplate for market loss modeling

This app has a simple index page which is rendered from a template by flask.
The actual api call is to the getloss end point which invokes the loss
model and returns the result as a json.

Includes logging.

## To run
```pip install -r requirements.txt```<br>
```mkdir log```<br>
```python app.py```<br>

## To Test
```curl -X GET http://localhost:8000/```

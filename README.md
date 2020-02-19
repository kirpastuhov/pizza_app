PizzaApp
===


## Getting started
Get yourself a copy and create virtual enviroment by pasting the following lines into your terminal:

``` 
git clone https://github.com/kirpastuhov/pizza_app.git
cd pizza_app
virtualenv env
source env/bin/activate
```

Install all requirments

```
pip3 install -r requirments.txt
```
Make migrations
```
 python3 manage.py migrate
```
And now you are ready to run the server

```
python3 manage.py runserver
```
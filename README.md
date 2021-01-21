# Django_Multiple_User_Type



# Decorator
```javascript

fucntion based Views : @customer_required @login_required
class based views    : @method_decorator([login_required, customer_required], name='dispatch')


```


## Run

'''javascript

python manage.py makemigrations
python manage.py migrate
python manage.py runserver

'''
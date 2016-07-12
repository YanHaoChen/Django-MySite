# Django-MySite

This project is used to practice how to build a web application with Django. It will follow the Django offical tutorial and be finished step by step.

## Environment
Use [Django_Env](https://github.com/YanHaoChen/Django-MySite/tree/master/Django_env) to setup the virtual environment with Django.

### Activate
```shell
$ source Django_Env/bin/activate
```
### Deactivate
```shell
$ deactivate
```
### Package
```shell
Django (1.9.7)
django-bootstrap3 (6.2.2)
djangorestframework (3.3.2)
pip (8.1.2)
setuptools (18.2)
wheel (0.24.0)
```

## Running the server
You can use those commands to run the server.
### Default
You can see the web application with your Web browser.([http://127.0.0.1:8000/](http://127.0.0.1:8000/))

```shell
$ python manage.py runserver
```

### Changing the Port
```shell
// python manage.py runserver <port>
$ python manage.py runserver 8080
```
### Changing the IP
```shell
// python manage.py <IP>:<port>
$ python manage.py 0.0.0.0:8080
```

## Learning Stage

Part | Status | Link
--- | --- | ---
1. Create a Project | Complete | [see](https://docs.djangoproject.com/en/1.9/intro/tutorial01/)
2. Database and Site of Admin | Complete | [see](https://docs.djangoproject.com/en/1.9/intro/tutorial02/)
3. Using Template | Complete | [see](https://docs.djangoproject.com/en/1.9/intro/tutorial03/)
4.   | Not Yet | [see](https://docs.djangoproject.com/en/1.9/intro/tutorial04/)
5.   | Not Yet | [see](https://docs.djangoproject.com/en/1.9/intro/tutorial05/)
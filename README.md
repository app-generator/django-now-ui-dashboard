# [Django Dashboard NowUI](https://www.youtube.com/watch?v=XUNiLhk31kY)

**Open-Source Admin Panel** coded in **Django Framework** on top of **NowUI Dashboard** design. **Features**:

- SQLite, Django native ORM
- Modular design
- Session-Based authentication (login, register)
- Forms validation
- UI Kit: **NowUI Dashboard** provided by **Creative-Tim**

<br />

![Django Dashboard NowUI - Open-Source Web App.](https://raw.githubusercontent.com/app-generator/static/master/products/django-dashboard-nowui-intro.gif)

<br />

## How to use it

```bash
$ # Get the code
$ git clone https://github.com/app-generator/django-dashboard-nowui.git
$ cd django-dashboard-nowui
$
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv --no-site-packages env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv --no-site-packages env
$ # .\env\Scripts\activate
$ 
$ # Install modules
$ # SQLIte version
$ pip3 install -r requirements.txt
$
$ # Create tables
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Start the application (development mode)
$ python manage.py runserver # default port 8000
$
$ # Start the app - custom port
$ # python manage.py runserver 0.0.0.0:<your_port>
$
$ # Access the web app in browser: http://127.0.0.1:8000/
```

<br />

## Docker execution

@WIP

<br />

## Credits & Links

- [Django Dashboard NowUI](https://www.youtube.com/watch?v=XUNiLhk31kY) - yTube presentation
- [Django Framework](https://www.djangoproject.com/) - Offcial website

<br />

## License

@MIT

<br />

---
[Django Dashboard NowUI](https://www.youtube.com/watch?v=XUNiLhk31kY) - provided by **AppSeed**

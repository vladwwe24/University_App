# University_App
Welcome to my University Project 

There is an application for institute of the Physics and Mathematics

[Features]:
1. User can be redirected to the page with documentation and other information about the course
2. The server should add your IPv4 to the ALLOWED_HOSTS automatically

How to use it:
[Precondition steps]:
You should have the Python v3.7
The "virtualenv" lib should be installed to your Python packages
"pip install virtualenv" <-- Use this command


[Step to use it]:
1. There is installed virtual environment
2. Go to the "venv" dict
3. Activate the environment use this command --> "source .\Scripts\activate" or ".\Scripts\activate"
4. Go to the "MyApp" dict
5. Open Shell Window in this folder (Shift + Right mouse button)
6. Run this command --> "python manage.py runserver 0.0.0.0:8000" (now your personal server is activated)
7. Find out your IPv4 (in cmd run --> "ipconfig")
8. Go to the browser and enter this IP-adress + :8000 to the url-field


After all this steps you should be redirected to the main page of the web-app


Also you can have following errors or problems:
1. If after leading to the page you have error message:
	a) Go to the "MyApp" folder in the folder with the same name
	b) Find there the "setting.py" file
	c) Open it
	d) Scroll down the window to the "ALLOWED_HOSTS = ip_checker()" string
	e) Change it --> "ALLOWED_HOSTS = ['*here should be you IPv4*']"

2. You can have problem with activation of the virtualenv (Try to do this in the CMD or Shell)


If you have other type of error, just call or write me:
vladwwe24@gmail.com or hryhorovych.vlad@gmail.com

# week2

---
## Commands:

``` terminal
python manage.py startapp tutorial
```
1.  Open a terminal or command prompt and navigate to the root directory of your Django project.
2.  Run the `python manage.py startapp <app_name>` command, where `<app_name>` is the name of your new app. For example, `python manage.py startapp blog`.
3.  The `startapp` command will create a new directory with the name of your app, containing several files and directories that make up the basic structure of a Django app.
4.  You can then modify the files in your new app to provide the desired functionality. For example, you might create models in the `models.py` file, views in the `views.py` file, and templates in the `templates` directory.
5.  After you have made changes to your new app, you will need to add it to the `INSTALLED_APPS` list in your project's `settings.py` file to include it in your project.
Overall, the `startapp` command is a useful tool for organizing your Django project into smaller, reusable components that can provide specific functionality.

Django, the `python manage.py startapp` command is used to create a new Django app. An app is a self-contained module that can provide specific functionality to a Django project, such as user authentication, content management, or search.

- create another folder: `tutorial` in this case.
- one project can have as many apps as you want
- `urls.py`
- `admin.py` everything for administration side
- `model.py` all models set in this folder only
- `viewer.py` all display pattern in this folder
- `test.py` all tests run in this folder
To create a new app using the `startapp` command, you can follow these steps:



``` terminal
python manage.py migrate
```
to initialise as an administrator level,  `db.sqlite3` is created, it is a SQLite DB

``` terminal
python manage.py createsuperuser
```
to create a admin user [[superuser]], and then set up your username and password

``` terminal
python manage.py runserver
```
to start the development server, a link will be generated, and open the link with a web browser, follow with `/admin`, then enter into ui page


## to-dos
- [ ] ~~use VSC in Pycharm to share the project with GitHub~~
- [ ] ~~push used GitHub Desktop as Pycharm only created a empty remote folder~~
- [ ] ~~database SQLite in Pycharm, find the file created earlier~~
- [ ] create a superuser
- [ ] create a new app
- [ ] create a new model
- [ ] create a new view
- [ ] create a new template
- [ ] create a new url
- [ ] create a new admin
- [ ] create a new test


 

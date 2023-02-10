

# Hello World Django App Project

This is a simple Django app that returns a JSON object with the message "Hello World!".


## Requirements & Installation
We have to install some pre-requirements to run this Django Hello World project.
 
To use virtual environments run following command in your terminal:

```bash
  pip install virtualenv
```
Creating a new virtual environment by running following command. (In place of myprojectenv give any name)
```bash
  virtualenv myprojectenv
```
Activating created virtual environment by running following command:
```bash
  .\myprojectenv\Scripts\activate.ps1
```
Installing Django framework by running following command:
```bash
  pip install -r .\requirements.txt
```
Now run:
```bash
  python manage.py migrate
```
After running above command you will now see:
```bash
Operations to perform:
  Apply all migrations: admin, auth, contenttypes, sessions
Running migrations:
  Applying contenttypes.0001_initial... OK
  Applying auth.0001_initial... OK
  Applying admin.0001_initial... OK
  Applying admin.0002_logentry_remove_auto_add... OK
  Applying admin.0003_logentry_add_action_flag_choices... OK
  Applying contenttypes.0002_remove_content_type_name... OK
  Applying auth.0002_alter_permission_name_max_length... OK
  Applying auth.0003_alter_user_email_max_length... OK
  Applying auth.0004_alter_user_username_opts... OK
  Applying auth.0005_alter_user_last_login_null... OK
  Applying auth.0006_require_contenttypes_0002... OK
  Applying auth.0007_alter_validators_add_error_messages... OK
  Applying auth.0008_alter_user_username_max_length... OK
  Applying auth.0009_alter_user_last_name_max_length... OK
  Applying auth.0010_alter_group_name_max_length... OK
  Applying auth.0011_update_proxy_permissions... OK
  Applying auth.0012_alter_user_first_name_max_length... OK
  Applying sessions.0001_initial... OK
```
Changing the directory to helloworld_project by running following command:
```bash
  cd .\helloworld_project\
```

## Run Django App
Now run following command in your terminal:
```bash
  python manage.py runserver
```
Open your web browser and go to http://127.0.0.1:8000/ to see the Hello World message in JSON format like below:
```bash
  {"Message": "Hello World!"}
```

## Conclusion
That's it! You have successfully created a Hello World Django app that returns a JSON object with the message "Hello World!".
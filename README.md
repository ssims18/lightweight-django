# lightweight-django
O'Reilly Lightweight Django

## Chapter 1

Setup a lightweight Hello World project and create it as a Django project template.

Disable the `DEBUG` setting via environmental variable.

```bash
export DEBUG=off
```

Set the `ALLOWED_HOSTS` environmental variable to validate incoming HTTP HOST header values. The comma separated list configuration allows for multiple hosts.

```bash
export ALLOWED_HOSTS=localhost,example.com
python hello.py runserver
```

### Template File

Hello.py is saved as a simple Django project template file. To use with `startproject`, add the `--template` argument.

```bash
django-admin.py startproject foo --template=project_name
```

This should create a _foo.py_ file inside of a _foo_ directory.

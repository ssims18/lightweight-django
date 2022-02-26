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

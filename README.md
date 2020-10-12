# Steps to setup
```
cd docker
./exec build
./exec restart
./exec manage.py migrate
./exec manage.py collectstatic
./exec manage.py createsuperuser
./exec bserver
```

edit /hosts file in host machine, add:
```
127.0.0.1       project.test
```

Then access this url on browser:
https://project.test/admin

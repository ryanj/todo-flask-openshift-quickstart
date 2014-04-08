## HDP Todo Application##

A simple todo application built using Python 2.7 , Flask, and Twitter Bootstrap.Adapted to use a hadoop back-end for storing data.

1. Create the application using 
```bash
$ rhc app create todo python-2.7
```

2. Pull the source code from github
```
$ git remote add upstream -m remote-hdp-backend https://github.com/ryanj/todo-flask-openshift-quickstart.git
$ git pull -s recursive -X theirs upstream master
```

3. Push the resulting application to OpenShift:
```
$ git push
```

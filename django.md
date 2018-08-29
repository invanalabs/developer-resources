# Django Notes



### Delete the migrations recursively from all apps
```
find . -path "*/migrations/*.py" -not -name "__init__.py" -delete
find . -path "*/migrations/*.pyc"  -delete
```


### dumping the data
```
python manage.py dumpdata --natural-foreign --natural-primary -e contenttypes -e auth.Permission -e admin.logentry -e sessions.session --indent 4 > initial_data.json
```

# Normalize all the line endings (Changes for Git in Windows)
```
git config core.fileMode false
```
```
git add --renormalize .
git commit -m "Normalize all the line endings"
```
```
git reset --hard HEAD
```

# Start migrations
```
python manage.py makemigrations
```
```
python manage.py migrate
```


# Start create superuser
```
python manage.py createsuperuser
```
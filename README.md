# clubrepo
Simple web app that allows to display &amp; add/modify/remove clubs 

## Technologies :

* Flask (python +3.13)
* Poetry (for library management)
* MongoDB
* Docker

## Useful git commands :

Retrieve latest changes in current git branch
```
Git pull
```

Change branch
```
git checkout <branch_name>
```

Add, commit and push modifications
```
git add . && git commit -m " Your message here" && git push
```

## Deploy app

### Docker

#### Make sure to have installed docker

go to the docker directory
``` cd docker ```

run the docker compose
```
docker compose up
```


### Manual

#### Make sure to have installed python and poetry.

```
poetry run python run.py
```







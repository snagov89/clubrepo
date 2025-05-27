# Club~Repo
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

## NOT TO DO

**Do not push to the main branch without creating a new branch for each modification**

### Instead when adding/fixing something do the following :

* Create new issue in the 'Issues' tab in gitlab. Add a title and description
* On the right side, there should be a 'development' thing. Click the 'create new branch' and create a branch
* Change your branch to the newly created branch : git checkout <new branch>
* After you finished adding changes, you can merge the branch into main after a club member verifies the changes

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







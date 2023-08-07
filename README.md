### To create a venv
```
 conda create -p venv python==3.8 -y 
 ```

```
 git init
 
```

### for bash terminal


``` 
touch requrements.txt    --> To create the file 
```

```
touch .gitignore 
```


```
 touch README.md
```


#### for new dvc project to inititalize
```
dvc init
```

#### to add a file in dvc project
```
dvc add
```

#### to do multiple experiment
```
dvc repro   -> By using dvc.yaml  --> it will create a dvc.lock file with all the stages and hash no for 
tracking
```

#### to push dvc into remote location or url
```
dvc push
```

#### to add url or repo
```
dvc remote add "url"
```

#### To show the directed acyclic graph 
```
dvc dag

```

#### linux bash command 
```
mkdir /tmp/dvcstore    --> for making the remote location inside local

dvc remote add -d myremote /tmp/dvcstore    ---> adding that location to dvc for storing data

```
#### then push the chnages to dvc ..
```
dvc push
```
### 

```
git checkout <key>  --> for key : Run : git log
.
.
.

dvc checkout  --> it will change the data or files within the local by previous commit changes 

```

## Link of the DVC documentation
```
https://dvc.org/doc/start/data-management/data-versioning

```
### DVC Studio link
```
https://dvc.org/doc/studio/user-guide/projects-and-experiments/explore-ml-experiments
```
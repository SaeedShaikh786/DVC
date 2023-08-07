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

### 
```
git checkout <key>  --> for key : Run : git log
.
.
.

dvc checkout  --> it will change the data or files within the local by previous commit changes 

```

# devopsNOTES
## FILTER USE IN DEVOPS
###### CAT TO DISTPLAY A FILE CONTENT
``` 
cat VIIT.txt
```

###### grep  this id ==s use to search for a word in group of ile or a single file
```
grep -R SELENUX /ETC/*
```
remember linux id case sensitive
usin grep to get into directory
```
grep -i fireware anaconda.cfg
```
use this to ignore
```
grep -vi fireware anaconda.cfg
```

###### less is a reader
```
less anconada.cfg
```

#### head is reader that show the staRT OF A FILE
```
head vagrantfile
```
> to see the first 20 line 
```
head 20 vagrantfile
```


## I/O REDIRECTION
output redirection to a file
```
date > /temp/systeminfo.txt
```
to append to a file

```
>>
```
to redirect & append all the output to file (Output & Error both)

```
&>>
```
 
###### pipe in linux 
used to connect to command
total number of list of files in a directory
```
ls -l | wc -l
```
find host in the list of files
```
ls -l | grep host
```


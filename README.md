create new env
==============
```bash
conda create -n wineq python=3.7 -y
```
for activating the env
======================
```bash
 conda activate wineq
```
for deactivate env
=================

```bash
conda deactivate
```

#install requirement

```
pip install requirements.txt
```
```
git init
dvc init

dvc add data_given/winequality.csv

```

#what ever is present my current working directory add to the stagine area
```
git add .
git commit -m "first commit"
```
#for any update 
```
git add . && git commit -m "update Readme file"
```
```buildoutcfg
git remote add origin https://github.com/username/<reponame>.git 
git branch -M main
git push origin main
```

onliner update for readme
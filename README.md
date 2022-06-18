## Machine_Learning_Project

### Software and account Requirements.

1. [GitHub Account](https://github.com/)
2. [Heroku Account](https://id.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT Cli](https://git-scm.com/downloads)

### Creating conda environment

>Note: '-p' will create enveronment here it self, so you can del from here it self here we have used 'venv' name
```
conda create -p <env_name> python==3.7 -y
```
    
```
conda activate venv/
```

* Create a requirements.txt file

Add 'Flask' in requirements.txt 
```
Flask
```

```
pip install -r requirements.txt
```

Run
```
python app.py
```


To Add files to git staging area '.' will add all file
```
git add <file_name or . > 
```

>Note: To ignore files or folders from git we can write those file/folder names in '.gitignore' file


To check all versions maintained by git
```
git log
```        

```
git status
```

To create version/commit all git
```
git commit -m "meaaage"
```

>Note: 'origin 'is a variable clone URL will store in this origin variable 

To check remote 'URL or orgin'
```
git remote -v 
```


To check branch name
```
git branch 
```

```
git push origin main
```


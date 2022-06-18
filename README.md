## Machine_Learning_Project

### Software and account Requirements.

1. [GitHub Account](https://github.com/)
2. [Heroku Account](https://id.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT Cli](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)

### Creating conda environment

>Note: '-p' will create enveronment here it self, so you can del from here it self here we have used 'venv' name
```
conda create -p <env_name> python==3.7 -y
```
    
```
conda activate venv/
```

### Create a requirements.txt file

Add 'Flask' in requirements.txt 
```
Flask
```

```
pip install -r requirements.txt
```

### Run
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

### To Setup CI/CD pipeline in heroku we need 3 information

1. HEROKU_EMAIL = sudheer.ece2008@gmail.com
2. HEROKU_API_KEY = d613f329-167d-4e4e-8328-298eb518ca98
3. HEROKU_APP_NAME = ml-regression-app-suri


### BUILD DOCKER IMAGE

>Note: Image name for docker must be lowercase
```
docker build -t <image_name>:<tagname> .
```

To list docker image
```
docker images
```

### RUN docker image
```
docker run -p 5000:5000 -e PORT=5000 <image_id>
```

To check running containers in docker
```
docker ps
```

To stop docker container
```
docker stop <container_id>
```


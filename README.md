# udacity_repo
This is a repository include list of important commands for git, Github, etc.

## git Commands
* git clone
* git status
* git add
* git commit -m
* git push

#### Update with Token

## Adding New git Commands on 12-1-24
#### git commands
* git remote -v -> Check if the remote URL is configured correctly:
* git checkout -> swich branch
* git checkout -b -> create and switch to branch
* git push
* git push origin
* git push --set-upstream orgin -> make branch available on remote repository (GitHub)
* git remote add origin https://<your-token>@github.com/your-username/your-repository.git ->Use the command to add the remote URL with your fine-grained personal access token.
  * Alternative
```  
 export GITHUB_FINEGRAINED_TOKEN=your-fine-grained-token
```
```
 git remote add origin https://$GITHUB_FINEGRAINED_TOKEN@github.com/your-username/your-repository.git
```

## Anaconda Commands:

### Create a new conda environment
* conda create --name myenv python=3.9

### List all conda environments
* conda env list

### Remove an environment
* conda env remove --name myenv

### Export environment to YAML file
* conda env export > environment.yml

### Create environment from YAML file
* conda env create -f environment.yml

### Activate/Deactivate
* conda deactivate
* conda eactivate

### Requirements.txt Generation
* pip freeze > requirements.txt
* pip install -r requirements.txt

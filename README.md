# Quick Start
Duplicate the template Docker compose file
```
cp compose.template.yaml compose.yaml
```

Edit the compose.yaml with your repository and Github Personal Access Token
```
nano compose.yaml
```

Start the Docker compose setup and specify the number of runners to launch
```
docker compose up --scale runner=n # where n is the number of runners you want to run
```



Based on https://github.com/beikeni/github-runner-dockerfile but with my own labor because I wanted to learn more.
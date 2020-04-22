# Docker compose file to Create a ArangoDB cluster


* `git clone https://github.com/Wathsara/Docker-Composer-ArangoDB-Cluster.git`
* `cd Docker-Composer-ArangoDB-Cluster`
* `sudo docker-compose -f ./arango-cluster-docker-compose.yaml up`
* For the webUI
If Local machine - Go to `localhost:8000`
Else Go to `ExternalIP:8000`
> Can use any port matched in coordinates in yaml file. [8000,8001,8002]
* Give the root as the username, keep the password feild empty and press login.

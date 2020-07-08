# docker-dev-training
Docker training applied to dev team

1. Containerization Technique
   - Docker-hub (https://docs.docker.com/docker-hub/)
 
2. Docker basic commands (https://docs.docker.com/engine/reference/commandline/docker/)
   - Docker (Run/pull/build/inspect/logs)
   - Volumes (Data persistent)
   - Network
 
3. Dockerfile (https://docs.docker.com/engine/reference/builder/)

4. Docker Compose (https://docs.docker.com/compose/)
   - Stop/Start/Build
   - Shared Network
   - Shared Volumes
   - Running multiple containers, for example: apps, db
 
5. Best Practices (https://docs.docker.com/develop/dev-best-practices/)
6. Docker for Java devs (https://github.com/docker/labs/tree/master/developer-tools/java/)
7. Docker API (https://docs.docker.com/engine/api/)

## Suggested Challenge:

1. Build an web app in the language/version/library of your preference (I recommend use a language linux native);

2. This web app must be prepared to run inside a docker container;

3. This app should be able to run as many containers we want;

4. This web app must be accessible by browser (through the IP), should have a button to upload an image, the image must been saved locally (inside of the containers), however this path must a volume shared between both containers;

5. The web app should save the name and/or path into the mysql database (table); Overall the challenge suggest the creation of 3 containers (2 web apps and 1 db);

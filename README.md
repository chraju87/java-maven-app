1. Exec into Jenkins Docker container
   docker exec -u 0 -it <container_id> bash

2. apt-get update

3. apt-get install gettext-base

4. Check envsubst command after installation inside docker container, it will not print any output.

5. Create Secret for Docker Hub Registry

   kubectl create secret docker-registry my-registry-key --docker-server=docker.io --docker-username=chraju --docker-password=Satellite@108
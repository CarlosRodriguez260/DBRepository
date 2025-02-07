# DBRepository
# To run instance of postgressql and docker:
   - Put in the cmd: "docker run --name test -e POSTGRES_PASSWORD=dbuser -p 5432:5432 -d postgres"
       - Example from docker image in my docker hub: "docker run --name test -e POSTGRES_PASSWORD=dbuser -p 5432:5432 -d carlosrodriguez260/databasescourse:db1"
       - This will install a postgres instance on docker, and containerize it.
       - Then you can use datagrip and postgressql to look up the database
# To tag an image 
   - Put in the cmd: "docker tag <local-image>:<tag> <docker-hub-username>/<repository-name>:<tag>"
# To push a tagged image
   - Put in the cmd: "docker push <docker-hub-username>/<repository-name>:<tag>"
# To build an image to a container
   - Put in the cmd: "docker build -t <type_name_of_choice> ."

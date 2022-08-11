# Setup your Symfony application with Docker



## Lets do it step by step.
- ### Clone this repository to your machine;
- ### Go to `php/Dockerfile` and change the git `email` and `name`;
- ### Go to `docker-compose.yml` and change the `databasename_db` and `projectname`;
- ### Now, run the `docker-compose.yml`
- ### Open a bash terminal in your php container that you have just created;
- ### Type `symfony check:requirements`; You must see a green message saying ' Your system is ready to run Symfony projects'.
- ### Run this command `composer create-project symfony/skeleton .`;
- ### Access `http://localhost:8080/`;


## Done! 
## Now you have your Symfony application working!
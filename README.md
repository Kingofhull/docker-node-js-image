# Dockerizing a node js project
## The steps below will guide you on how to Dockerize a node js application
### step1
- since i already have my EC2 instance running, i just opened the EC2 intance and i set my path to 3000 and copied the IPV4 address
- i went to my gitbash terminal and shh into my EC2 instance and became a root user
- i installed git into my EC2 instance
- i cloned this url https://github.com/Helen-Chuks/express-api-starter
- then i switched to the repository "express-api-starter"
- then i created my Dockerfile and added instrutions that will help create a custom image inside it
- i created docker-compose.yaml file and added instructions to it
- then i ran the docker-compose command
- then i went back to my EC2 intance to copy my IPV4 address, went to the browser and paste it adding ":3000" that is the path.
- and it was successful, see image below
  

# ofn-docker
Open Food Network production deployment, based on Docker Compose


# getting things running locally to start building your community's local food hub

install git and docker first,
https://help.github.com/articles/set-up-git/

git clone https://github.com/LocalFoodSupply/ofn-docker.git
cd ofn-docker

# make sure your environment variables are configured
eval $(docker-machine env) 

Development Environment:

gett docker server agent running on your locak machine

user docker-machine start  

docker-compose up

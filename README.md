# apioak-docker
    docker run -d -p 10080:10080 -e DB_HOST= -e DB_PORT= -e DB_NAME= -e DB_USER= -e DB_PASSWORD=  apioak/apioak:latest

# docker-compose
    git clone https://github.com/apioak/apioak-docker.git
    cd docker
    docker-compose up 

# build 
    git clone https://github.com/apioak/apioak-docker.git
    cd docker
    docker-compose -f docker-compose-build.yml up 


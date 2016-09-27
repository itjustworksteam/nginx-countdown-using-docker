# nginx-countdown-using-docker

- If you want to run the result, you must have docker installed on your machine
- to install docker go to https://www.docker.com and follow the instructions

## compile and run this project

    git clone https://github.com/itjustworksteam/nginx-countdown-using-docker.git
    cd nginx-countdown-using-docker/
    docker build -t <name_that_you_want> .
    docker run -d -p <port_out>:<port_in> <name_that_you_want>
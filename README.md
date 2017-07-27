# docker-arm-prometheus
A docker image source repository for prometheus in raspberry pi 3

# Usage
git clone the repository by 
    
    git clone git@github.com:swapnil96/docker-arm-prometheus.git
    

# Commands
Use the following to deploy prometheus using the yml file provided in the repo.

    docker run -p 9090:9090 -v docker-arm-prometheus/prometheus.yml:/etc/prometheus/prometheus.yml swapnil18/docker-arm-prometheus





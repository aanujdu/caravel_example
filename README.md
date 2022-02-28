
# Caravel User Project

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![UPRJ_CI](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml) [![Caravel Build](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml)

| :exclamation: Important Note            |
|-----------------------------------------|

## Please fill in your project documentation in this README.md file 

Setup:
1. Installing Docker (https://docs.docker.com/engine/install/ubuntu/#uninstall-docker-engine) \
Uninstall any existing Dockers installations first by \
a. sudo apt-get purge docker-ce docker-ce-cli containerd.io \
b. sudo rm -rf /var/lib/docker \
c. sudo rm -rf /var/lib/containerd \
Install Docker using repository \
a. sudo apt-get update \
   sudo apt-get install \\ \
    ca-certificates \\ \
    curl \\ 
    gnupg \\ \
    lsb-release \
b. curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg \
c. echo \\ \
     "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \\ \
     $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null \\ \

d. sudo apt-get update \
e. sudo apt-get install docker-ce docker-ce-cli containerd.io \
To check if it is properly installed run \
sudo docker run hello-world \
Making Docker work without sudo (https://docs.docker.com/engine/install/linux-postinstall/) \
a. sudo groupadd docker \
b. sudo usermod -aG docker $USER \
c. newgrp docker \
d. docker run hello-world \
Install git version>2.5 \


Need to add the required stuff for my own project [FOR CLEARING PRECHECK]

Refer to [README](docs/source/quickstart.rst) for a quick start of how to use caravel_user_project

Refer to [README](docs/source/index.rst) for this sample project documentation. 

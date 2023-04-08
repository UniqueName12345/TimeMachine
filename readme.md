# TimeMachine
A digital time machine for the old internet. 

## How to use:
0. Installing and running Docker: Docker is a software platform that allows you to create, deploy, and run applications in containers. To use it, you first need to install it on your computer by downloading and installing the appropriate version for your operating system. Once installed, you can run Docker by opening the command-line interface and typing in the appropriate command. 
 
1. Running the `docker pull` command: This command is used to download a Docker image from a repository. In this case, the command `docker pull cttynul/waybackproxy:latest` is used to download the latest version of the WaybackProxy image from the Docker Hub repository. 
 
2. Running the `main.py`  script: This command is used to run a Python script named `main.py`  in the current folder, which is the folder where the Docker image was downloaded in step 1. This script is used to start the WaybackProxy server in the Docker container, which allows you to access the Wayback Machine through a proxy server. To run the script, open the command-line interface, navigate to the directory where the script is located, and type `python main.py`.
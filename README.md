# Url Shortener

Link shortening service will convert long url in shortcode and redirect to actual url using short code url.

## Installation

#Prerequisite:-
Linux Ubuntu 16.04
Docker version 18.09.7
docker-compose version 1.24.1

## Step

##############Login to Host Machine##############
**************Run the command**************
docker login --username=harshmunna

password : July@2019(NOTE*************)

Enter your password when prompted. If everything worked you will get a message similar to

WARNING: login credentials saved in /home/username/.docker/config.json
Login Succeeded

##############Start Private Microservices##############
**************Run the command**************
export IP=(`hostname -I | awk '{print $1}'`)
IP=$IP docker-compose -f docker-compose.yml up -d

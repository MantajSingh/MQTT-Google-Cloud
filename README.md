use the following command to install MQTT in Linux.

sudo apt-get update

sudo apt-get install mosquito

sudo apt-get install mosquitto-clients

sudo mosquitto –v

to use the MQTT to transfer data to other computers, you need to add the two lines in the mosquito.conf file it is in etc /mosquitto

listener 1883

allow_anonymous true

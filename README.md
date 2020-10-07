# wordpress-eaa-docker
a docker compose file with wordpress mysql and EAA

you can use port 80 if you're stuck but make sure that port is not in use.
And when the new EAA image has been commited, you can make the connector part of the docker-compose setup.

Just bring down your setup with "docker-compose down". Remove the current eaa connector "docker rm <eaa connector".
uncomment the eaa_connector part and a "docker-compose up -d" will start wordpress, mysql and the eaa connector.

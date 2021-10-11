# FHIR
According to the instructions given in mail
Downloaded HAPI FHIR server to my local unix box.
Created postgres image from docker hub using docker pull postgres.
In the same way downloaded Synthea Patient Generator code.
Changed the Database deatils to postgres in application.yml file as above.
Created one docker image for FHIR project using the below command
 ./build-docker-image.sh
Created Docker compose with all these three DB,FHIR and synthetic generator.
Created make start file using docker-compose up
Created make stop file using  docker-compose down

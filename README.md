# FHIR
According to the instructions given in mail
1. Downloaded HAPI FHIR server to my local unix box.
2. Created postgres image from docker hub using docker pull postgres.
3. In the same way downloaded Synthea Patient Generator code.
4. Changed the Database deatils to postgres in application.yml file as above.
5. Created one docker image for FHIR project using the below command
   ./build-docker-image.sh
6. created Docker compose with all these three DB,FHIR and synthetic generator.
7. Created make start file using docker-compose up
8. created make stop file using  docker-compose down

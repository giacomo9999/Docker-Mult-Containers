Node app (simple counter) using Redis, composed using Docker Compose into multiple local containers.  

To build component files:  
docker build -t giacomo9999/visits:latest .  

To run component files:   
docker run redis  
docker run giacomo9999/visits  

To build composed app:  
docker-compose build  
docker-compose up  
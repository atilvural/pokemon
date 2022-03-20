# pokemon
There are 2 projects related.<br />

Web -> https://github.com/atilvural/pokemon-web<br />
Service -> https://github.com/atilvural/pokemon-service<br />

# How to run
You can either run projects individually to debug or you can use docker-compose

# Docker Compose
1 - creating service image<br />
cd {path}/pokemon-service<br />
gradle build <br />
docker build -t pokemon-service:latest .<br />

2 - creating web image<br />
cd {path}/pokemon-web<br />
docker build -t pokemon-web:latest .<br />

3 - Running<br />
cd into docker-compose file location then run<br />
docker-compose up -d<br />


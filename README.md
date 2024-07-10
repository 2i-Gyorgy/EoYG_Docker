This project is about learning Docker and to achieve my 1st EoYGs.
The react app comes from Craig (https://github.com/CraigMcleod2i/bin_world)

To dockerise
1. Execute `docker image build -t react-example-image:latest .` in project root.
2. To create and run container `docker container run -dp 3003:3000 --name react-example-container react-example-image:latest`
3. http://localhost:3003
4. To start existing container `docker start react-example-container`
5. To stop container `docker stop react-example-container`


Or alternatively use compose file
1. `docker compose up -d --build`
2. http://localhost:3003
3. To stop: `docker compose down`

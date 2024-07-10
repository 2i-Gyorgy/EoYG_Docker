This project is about learning Docker and to achieve my 1st EoYGs.
The react app comes from Craig (https://github.com/CraigMcleod2i/bin_world)

To dockerise, execute `docker image build -t react-example-image:latest .` in project root.
To create and run container `docker container run -dp 3003:3000 --name react-example-container react-example-image:latest`
http://localhost:3003
To start existing container `docker start react-example-container`
To stop container `docker stop react-example-container`

Or alternatively use compose file
`docker compose up -d --build`
http://localhost:3003
To stop: `docker compose down`

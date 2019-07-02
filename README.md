# Docker practice

`sudo docker build -f dev.Dockerfile .` - custom docker file

`sudo docker run -p 3000:3000 <id>`

`sudo docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app <id>` - references outside container


Example Dockerfile using [akkerman/rpi-nginx:wheezy](https://registry.hub.docker.com/u/akkerman/rpi-nginx/). 



optional: modify files in www directory

> docker build -t my-nginx-image .  
> docker run -p 80:80 --name my-nginx-container -d my-nginx-image 


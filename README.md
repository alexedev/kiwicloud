BUILD

`docker build -t kiwi_img .`

RUN

`docker run --name kiwi_cont -p 5001:80 -d kiwi_img`

the open `localhost:5001`

REMOTE image

https://hub.docker.com/r/buduguru/kiwi_cloud/

- Create github repo with readme file.

- Clone the repo with command
 #git clone repourl

- Docker login with command  
 #docker login
- Create one Dockerfile in repo
 #vim Dockerfile
 
- Create index.html file in the repo
 #vim index.html

- Build the image from nginx
 #docker build -t "chikku27/nginx1.0" .
 
- Launch the conatiner using this "chikku27/nginx1.0" image
 #docker run -it --name container1 chikku27/nginx1.0 /bin/bash
 
- Check the ip of container
 #hostname -i
 172.17.0.2
- And browse with
 172.17.0.2:80
 
- Push the image to dockerhub.
 #docker push chikku27/nginx1.0

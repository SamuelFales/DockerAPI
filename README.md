DockerAPI
Login on docker:
docker login https://docker.pkg.github.com -u samuelfales@gmail.com -p 'token'  

pull de image 
sudo docker pull docker.pkg.github.com/samuelfales/dockerapi/image:latest   

run 
 docker run --name netapi -p 7775:80 c25f9c07045b    
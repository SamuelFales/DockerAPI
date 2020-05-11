DockerAPI

1. SUBIR UMA API PARA GIT
2. CRIAR GIT ACTIONS
3. GERAR TOKEN
4. PULL DA IMAGEM 
5. AJUSTA PORTAS DE ENTRADA E SAIDA NO SO
5. RUN IMAGE


COMANDOS:
DENTRO DO CENTOOS:

Login on docker:
docker login https://docker.pkg.github.com -u USERNAME -p 'TOKEN GERADO'  

pull de image 
sudo docker pull docker.pkg.github.com/samuelfales/dockerapi/image:latest   

run 
 docker run --name netapi -p 7775:80 c25f9c07045b    
  

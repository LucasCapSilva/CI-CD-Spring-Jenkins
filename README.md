# CI-CL-Spring-Jenkins

## instalando jenkins via docker

entre na pasta docker

![alt text](https://i.imgur.com/bypxe7K.png)

abra o terminal e digite os seguintes comandos

docker build -t jenkins_marcelo:latest .

docker-compose -f docker-jenkins.yml up

## configurando jenkins

abra o jenkins na porta:

http://localhost:8080

coloque o Unlock Jenkins

![alt text](https://i.imgur.com/zzafKAt.png)

instale os pacotes nescessarios 

![alt text](https://i.imgur.com/rSuRMu5.png)

## crie um usuario jenkins

![alt text](https://i.imgur.com/GQAcL6u.png)

## instalando jdk e maven

em global tools configuration
instale jdk e defina seu usuario oracle
![alt text](https://i.imgur.com/uJeC06r.png)

instale maven 
![alt text](https://i.imgur.com/XrzU4DK.png)

## criando um job pipeline

![alt text](https://i.imgur.com/JQa4Ekz.png)

copie o codigo do arquivo txt da pasta pipeline
![alt text](https://i.imgur.com/wYyZ7eK.png)

cole em configuração pipeline
![alt text](https://i.imgur.com/GAVfL1A.png)

clique em construir agora
![alt text](https://i.imgur.com/TT5x0FH.png)






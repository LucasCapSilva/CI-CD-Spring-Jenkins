# CI-CD-Spring-Jenkins

Integração continua com Jenkins em app Spring/Java

## Instalando jenkins via docker

Entre na pasta docker

![alt text](https://i.imgur.com/bypxe7K.png)

Abra o terminal e digite os seguintes comandos

docker build -t jenkins_marcelo:latest .

docker-compose -f docker-jenkins.yml up

## Configurando jenkins

Abra o jenkins na porta:

http://localhost:8080

Coloque o Unlock Jenkins

![alt text](https://i.imgur.com/zzafKAt.png)

Instale os pacotes nescessarios 

![alt text](https://i.imgur.com/rSuRMu5.png)

## Crie um usuario jenkins

![alt text](https://i.imgur.com/GQAcL6u.png)

## Instalando jdk e maven

Em global tools configuration
Instale jdk e defina seu usuario oracle
![alt text](https://i.imgur.com/uJeC06r.png)

Instale maven 
![alt text](https://i.imgur.com/XrzU4DK.png)

## Criando um job pipeline

![alt text](https://i.imgur.com/JQa4Ekz.png)

Copie o codigo do arquivo txt da pasta pipeline
![alt text](https://i.imgur.com/wYyZ7eK.png)

Cole em configuração pipeline
![alt text](https://i.imgur.com/GAVfL1A.png)

configurando trigger

![alt text](https://i.imgur.com/1DgRBtj.png)

Clique em construir agora
![alt text](https://i.imgur.com/TT5x0FH.png)







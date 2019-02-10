#Radamanthys

O projeto tem como objetivo facilitar o desenvolvimento de aplicações laravel angular no docker. 

### O que eu vou precisar ter para executar o projeto ?

Basicamente você vai precisar instalar o [docker](https://docs.docker.com/v17.12/install/linux/docker-ce/ubuntu/#install-docker-ce) e o [docker compose](https://docs.docker.com/compose/install/#install-compose). Você vai precisar ter também um projeto laravel e angular instalado. Se desejar você também pode criar um projeto laravel ou angular de dentro dos containers.


### Como executar o projeto ?
  
Tudo que você vai precisar fazer é clonar o projeto, ir na pasta  docker-compose, copiar o docker-compose.yml e o env para a raiz do seu projeto laravel e angular 

#### exemplo

blog/

my-app/

.env

docker-compose.yml

Agora é só ir no .env e definir o nome da sua aplicação laravel, e o nome da sua aplicação angular, no exemplo dado o nome da minha aplicação laravel é blog, e nome da minha aplicação angular é my-app.

````
APLICATION_LARAVEL_NAME=blog
APLICATION_ANGULAR_NAME=my-app  
````

Depois é só executar 
````
 docker-compose up
```` 
:)






 
 Este projeto foi o primeiro realizado em Back-end, nele foram treinadas as habilidades e aprendizados do uso do Docker, os primeiros requisitos foram para escrever comandos dockers específicos e ao final do projeto o desafio 
 era criar os dockerfiles e um docker-compose juntando um container de front-end, um de back-end e um container de testes.

 Para acessar o projeto clone o repositório, acesse a pasta, instale as dependências e acesse os códigos criados dentro da pasta docker pelo vsCode.
 - git clone git@github.com:FernandaGrein/backEnd-Project-Docker.git
 - cd backEnd-Project-Docker
 - npm install 
 - code .

 Foram resolvidos os seguintes requisitos: 
 - Foi criado um container em modo interativo utilizando a imagem alpine.
 - Iniciado o container, mantendo-o ativo
 - Foi listado os container pelo nome
 - Foi executado os comando cat /etc/os-release
 - Foi removido o container criado
 - Foi feito o download da imagem nginx
 - Foi rodado o novo container renomeando-o e fazendo o mapeamento de portas
 - Foi parado o container 
 - Foi gerado uma build a partir do Dockerfile do back-end
 - Foi gerado uma build a partir do Dockerfile do front-end
 - Foi gerado uma build a partir do Dockerfile dos testes
 - Por fim foi criado um docker-compose, orquestrando as 3 imagens já buildadas

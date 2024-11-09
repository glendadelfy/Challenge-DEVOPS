GLENDA DELFY VELA MAMANI – RM 552667
LUCAS ALCÂNTARA CARVALHO – RM 95111 
RENAN BEZERRA DOS SANTOS – RM 553228

DEVOPS TOOLS E CLOUD COMPUTING
CHALLENGE - ODONTOPREV
SPRINT1

1. Solução Geral do Projeto 
O Projeto User em Dotnet MVC é uma API completa utilizando o Swagger, projeto User tem como base cadastrar usuários em um banco de dados Oracle.
 
![image](https://github.com/user-attachments/assets/8f64229f-1b62-4e2f-85d8-574bcce2b8b4)

2. Virtualização do Projeto 
A virtualização, seja através de máquinas virtuais ou containers Docker, oferece uma série de benefícios que podem potencializar a entrega e a manutenção do projeto User para a Odontoprev. Ao permitir a criação de ambientes de software isolados, a virtualização agiliza o desenvolvimento, facilita a escalabilidade e aumenta a flexibilidade da solução.
laaS: A infraestrutura como serviço (laaS) é fundamental para a implementação da solução, fornecendo os recursos computacionais básicos, como servidores virtuais, armazenamento e redes.











3. .NET – Máquina Virtual
A escolha de uma máquina virtual para a aplicação .NET MVC, utilizando o banco de dados Oracle. A VM precisa ter seu próprio sistema operacional, hardware e recursos dedicados. As vantagens de um sistema operacional são: alto nível de isolamento da aplicação, flexibilidade permitindo executar em qualquer sistema operacional, e tecnologia já utilizada no mercado. 
O ambiente de desenvolvimento é a IDE Visual Studio 2022 para a aplicação .NET, utilizando o sistema operacional Windows. A segurança também é um fator importante para a aplicação. 
Configurações do ambiente: .NET Framework, Banco de dados Oracle, um servidor Windows. A máquina virtual é a VM da Azure.
A imagem apresenta uma arquitetura de uma aplicação web hospedada na nuvem Azure, utilizando uma máquina virtual (VM).
 
![image](https://github.com/user-attachments/assets/c165404c-0b86-4d67-a5d2-8c6467b32c7c)








SPRINT2
4. Criação da Máquina Virtual

![image](https://github.com/user-attachments/assets/2c067b32-a5ac-42cd-89f3-aab8c757cf3d)


 

IP da maquina: 191.234.212.7
Admin: admglenda
Senha: Adminglenda123












5.Docker 
1. Imagens
 ![image](https://github.com/user-attachments/assets/b8d685cc-8c0e-4b2a-93b4-732bbd0d8c49)


2.Containers
 
![image](https://github.com/user-attachments/assets/45a6a8ae-80c4-43f6-b1e1-157bce841aad)



6.Comandos Utilizados 
docker build -t challenge-dotnet -f Dockerfile .
docker build -t challenge-dotnet  .
docker run -d -p 8080:8080 challenge-dotnet
docker compose up

docker build -t challenge-dotnet -f Dockerfile .
 

docker build -t challenge-dotnet  .
 
docker run -d -p 8080:8080 challenge-dotnet 
docker compose up
 








7.Github do projeto: https://github.com/glendadelfy/Challenge-DEVOPS.git
8.Video: https://youtu.be/YN5TJ77-HNY

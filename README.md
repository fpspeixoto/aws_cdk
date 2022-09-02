# Passos para rodar o CDK

Primeiramente é necessário criar uma conta na AWS.

## Criando um usuário no IAM
É necessário criar um usuário no IAM e selecionar o tipo de credencial da AWS com a opção 
"Chave de acesso: acesso programático". Após selecionar clicar na apa "Anexar politicas existentes de forma direta"
e selecionar a opção "AdministratorAccess".
Nos próximos passos não precisa marcar nada, porém no ultimo step é necessário guardar a chave publica e primária 
para as próximas etapas.
## Instalação do CDK no windows

### Pré instalação do CDK
Para realizar a pré instalação do CDK é necessário seguir o passo do link abaixo:
<a href="https://1drv.ms/b/s!AntJIJ8qkvN7sL0v8V3cP_5TaVFxgg?e=5BpoTn">LINK</a>

### Instalação do cdk
No diretório onde deseja instalar o arquivo CDK, execute o comando abaixo
    <br>
* cdk init app --language java (comando para criação do zero)<br>

Após roda o comando abaixo e inserir as chaves publicas e primadas conforme solicita no terminal
<br>
* aws configure 
* Para executar o projeto na aws diretamente da maquina basta rodar o comando:
"cdk deploy --parameters Rds:databasePassword=root * "


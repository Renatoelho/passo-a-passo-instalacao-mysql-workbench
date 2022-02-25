# Passo a passo de instalação do MySQL Workbench

### Requisitos mínimos para instalação:

>> Sistema operacional Linux (Ubuntu 20.04.2 LTS)  <br/>Memória RAM de 4GB ou mais

O <i>MySQL Workbench</i> é uma ferramenta utilizada para administração de bancos de dados <i>MySQL</i>, sua interface facilita a gestão de bancos locais e remotos, sendo necessário as credenciais de acesso como: ````usuário````, ````senha````, ````porta````, onde está sendo executado o serviço que por padrão é na 3306 e ````host/IP```` de localização do servidor.

![MySQL Workbench](https://drive.google.com/uc?export=view&id=1J3xWrC_DhF9Bb9Yp9OTR5GJ5n3k_HlZE)

# A instalação consiste nos seguintes passos:

## 1º Passo - Baixe o arquivo de instalação do <i>MySQL Workbench</i>

Faça o Download do arquivo de instalação ````...ubuntu20.04_amd64.deb````. Para evitar erros durante a instalação, execute o comando no terminal ````uname -a````, assim você saberá qual arquivo de instalação é compatível com seu sistema.

[Download MySQL Workbench]( https://dev.mysql.com/downloads/workbench/)

![Página Downloas MySQL Workbench](https://drive.google.com/uc?export=view&id=1IoD5DVAnIWCoo7vMNCHR8dbrR41HNNcG)

## 2º Passo - Execute a instalação

- Atualize o ambiente antes de iniciar o processo com os seguintes comandos:

````
sudo apt update && sudo apt upgrade –y
````

- Acesse a pasta de <i>Downloads</i> e execute o comando ````install````:

````
cd Downloads/
sudo apt install ./<arquivo baixado>.deb –y
````

![Instalação MySQL Workbech](https://drive.google.com/uc?export=view&id=1Ip1UILxYj3XeTGdG7OZNOLjQK1GgOfqm)

O **<i>MySQL Workbench</i>** foi instalado e já pode ser iniciado.

## 3º Passo - Primeiro acesso

- Abra o terminal e execute o comando:

````
mysql-workbench
````

![Primeiro Acesso MySQL Workbech](https://drive.google.com/uc?export=view&id=1Isl-4q0UtYL9YSv6BDtrV5NKQNH1-raY)

Pronto! O **<i>MySQL Workbench</i>** já está apto para as configurações de acesso.

## 4º Passo - Criando sua primeira conexão

Para fazer essa primeira conexão vamos acessar o banco <i>MySQL</i> que está sendo executado local, mas poderia estar em qualquer outro servidor.

**Dados para conexão:**
>> **Usuário:** ubuntu  <br/>**Senha:** *****  <br/>**Porta:** 3306  <br/>**Host:** 127.0.0.1

Em **<i>‘MySQL Connections’</i>** clique para adicinar uma nova conexão e preencha conforme a seguir:

![Primeira Conexão](https://drive.google.com/uc?export=view&id=1IzuOHT78Tx1l2LB6MBadFbO-bvlyjZgI)

Agora com a configuração feita, conforme no print anterior, clique **<i>‘Test Connection’</i>**.

![Testando Primeira Conexão](https://drive.google.com/uc?export=view&id=1J20M2SHaI5N6Ohw9VrH39obH1uFHlp0L)

Vamos executar alguns comandos **<i>SQL</i>** para testar nossa conexão.

![Comandos SQL](https://drive.google.com/uc?export=view&id=1J30q2qQxwlrEzuL624T88HDETOln7hxP)

Pronto! Tudo Ok.

Em breve voltarei para ensinar os principais comandos **<i>SQL</i>**, que ajudarão você a administrar seu servidor de banco de dados <i>MySQL</i>. 

**Até.**

**Referências:**  <br/><font size="1">  <br/>Dev.mysql.com, MySQL Workbench. Disponível em: <https://dev.mysql.com/downloads/workbench/>. Acesso em: 17 nov. 2021.  <br/>Dev.mysql.com. Docs MySQL Workbench. Disponível em: <https://dev.mysql.com/doc/workbench/en/>. Acesso em: 17 nov. 2021.  <br/></font>
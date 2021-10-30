# Semana Spring React

---

Bootcamp de 1 Semana criando um aplicação completa (Front-end e Back-end) utilizando diversas tecnologias.

**Instrutor:** Nélio Alves

Github do Bootcamp: https://github.com/devsuperior/sds5

## Ferramentas utilizadas:

- Java
- Typescript
- Spring Boot
- React
- PostgreeSQL (Banco de dados)
- Git (Versionamento de código)
- Postman (Auxiliar na construção de APIs)
- Maven (Gerenciador de pacotes para o Java)
- Node & NPM (JS para back-end + gerenciador de pacotes)
- Heroku CLI (Deploy)
- Curl
- VS Code

## Guia de Instalação das Ferramentas principais (Linux)

### Curl

- Instalar o curl:

```
sudo apt-get install -y curl
```

- Conferir a instalação:

```
curl
```

### Git

- Instalação:

```
sudo apt-get install -y git
```

- Conferir a instalação:

```
git
```

### Java JDK 11

- instalação:

```
sudo apt install openjdk-11-jdk
```

- Verificação:

```
java -version
```

- configuração path JAVA_HOME:

  - Verificar caminho Java:

  ```
  sudo update-alternatives --config java
  ```

  - Copie o caminho do Java
  - Edite o arquivo .bashrc:

  ```
  sudo gedit ~/.bashrc
  ```

  - Copie o código abaixo no final do arquivo e salve:

  ```
  JAVA_HOME =/usr/...
  export JAVA_HOME
  export PATH=$PATH:$JAVA_HOME
  ```

  - Abra um novo terminal e teste:

  ```
  echo $JAVA_HOME
  ```

### Maven

- Instalação:

```
sudo apt-get install maven
```

- Verificação:

```
mvn -v
```

### Spring Tools Suit

- Google: STS
- Baixar
- Descompactar (exemplo: /home/user/apps)
- Iniciar STS
  - selecione um workspace (ex: /home/user/Workspaces/ws-sts)
- Liberar permissão na pasta do workspace:

```
sudo chmod -R ugo+rw /home/user/Workspaces/ws-sts
```

### Postman

- instalar com snap:

```
snap install postman
```

### Postgreesql

```
https://www.postgresql.org/download/linux/ubuntu/
```

### pgAdmin

```
https://www.pgadmin.org/download/pgadmin-4-apt/
```

Heroku CLI

```
https://devcenter.heroku.com/articles/heroku-cli
```

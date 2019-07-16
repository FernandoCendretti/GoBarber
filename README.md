# GoBarber

## API Rest da Ferramenta de Gerenciamento de Barbearias

## Instalação

```
$ git clone https://github.com/FernandoCendretti/GoBarber.git
$ cd GoBarber
$ npm install || yarn
```

É necessário ter o postgres instalado, caso tenha o Docker, basta executar os comandos:

```
sudo docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```

Para executar o sistema basta executar o comando:

```
yarn dev
```

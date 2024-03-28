# Desafio Compass

Projeto desenvolvido usando Vue.js com objetivo de enviar informações de contato para uma API através de um formulário.


## Project Setup

### 1. Instalar dependencias

```sh
npm install
```

### 2. Execução

```sh
npm run dev
```

### 3. Acessar o projeto

- [http://localhost:5173](http://localhost:5173)

## API Setup

### 1. Clonar projeto

```bash
git clone https://github.com/micheltlutz/dev-challenge.git
```

### 2. Criar imagem

```bash
docker build -t "dev-challenge" .
```

### 3. Verifique se a imagem foi criada

```bash
docker images
```
### 4. Executar container

```bash
docker run -d --name dev-challenge-demo -p 8000:8000 dev-challenge:latest
```

### 5. Verifique se o container está em execução

```bash
docker ps
```

### 6. Acessar a API

- [http://localhost:8000](http://localhost:8000)

### Parar container

When you need to stop the container, run the code below in your terminal

```bash
docker stop dev-challenge-demo
```
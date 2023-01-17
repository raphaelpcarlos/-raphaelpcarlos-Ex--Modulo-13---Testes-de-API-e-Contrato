# Exercicio Módulo 13 Testes de API e Contrato

### Pré-requisito: Node JS e o Postman

### Instalação serverest
npm i serverest

### Inserir o seguinte comando no console:
npx serverest

### Para acessar basta abrir seu navegador com a seguinte
http://localhost:3000/ ou http://127.0.0.1:3000/


### Exercicio


• Mapeamentos dos principais cenários da funcionalidade Usuários;

• Considerando também, 2 cenários negativos;

• Inclusão das asserções em todos os testes;

• Utilização dos principais metodos (GET, POST,DELETE, PUT);

# ORDEM DA EXECUÇÃO DOS TESTES.

### POST - CADASTRAR USUÁRIOS

### GET - LOGIN

### GET - BUSCAR USUÁRIO POR ID

### GET - EDITAR USUÁRIO ( NECESSáRIO ID)

### GET - EXCLUIR USUÁRIO ( NECESSáRIO ID)

### VÁRIAVEIS GLOBAIS UTILIZADOS NO POSTMAN

LOCAL = URL http://localhost:3000

TOKEN = VARIAVEL SETADA APÓS A CHAMADA NA API LOGIN 

### COMANDO UTILIZADO

const resposta = pm.response.json()

pm.globals.set("token", resposta.authorization);


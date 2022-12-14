# Dogsgram

Esse projeto foi gerado com a versão 15.0.2 do [Angular CLI](https://github.com/angular/angular-cli).

## 🖥️ Preparando o ambiente

- Clone o repositório:

```
$ git clone https://github.com/fabioyamashita/dogsgram-angular.git
```

- Instale todas as dependências:

```
$ npm i
```

- Caso necessário, instale também o [JSON Server](https://www.npmjs.com/package/json-server):

```
$ npm i json-server
```

## Ambiente de Desenvolvimento

- Para conseguir utilizar o fake Back-end criado através do JSON Server, rode o seguinte comando no terminal:

```
$ json-server --watch dogs.json
```

- Em outro terminal, rode agora o server dev:

```
$ ng serve
```

Você poderá ver o projeto atráves da URL: `http://localhost:4200/`.

## Observações

O projeto foi criado em Angular e o JSON Server foi utilizado para atuar como o Back-End da aplicação, para possibilitar a persistência dos dados. O arquivo que será modificado é o `dogs.json`. Caso já tenha feito modificações no arquivo, você poderá consultar o original em `dogs-original.json`.

## Enunciado

O enunciado completo (em pt-br) está no arquivo [enunciado.md](https://github.com/fabioyamashita/dogsgram-angular/blob/main/enunciado.md).

## Solução

Você poderá ver abaixo a solução para cada proposição do projeto.

### Principal

Desenvolver uma aplicação em angular que permita Criar, Atualizar, Deletar e Visualizar itens dentro de um tema escolhido por você (não pode ser o mesmo de sala de aula);

- Visualizando os itens  
![dogsgram-list](https://user-images.githubusercontent.com/98363297/207473989-6df11c6e-909d-45a9-99f1-d2e6ca8ec8fa.gif)

- Criando um item  
![dogsgram-create](https://user-images.githubusercontent.com/98363297/207473998-1f1e1a4a-f8bd-4f25-8ad5-053817a99ce7.gif)

- Atualizando um item

- Deletando um item

Criar as rotas para Criar e Visualizar a listagem de itens;

Possuir um header para acesso a cada rota (o header deve ser marcado caso a rota esteja ativa);

Um pop-up deve ser aberto ao clicar tanto no botão de edição, quanto no de deleção de um item;

- Pop-up de edição
- Pop-up de deleção

Permitir a exclusão de um item através do menu de listagem;

### Extra!

O formulário deve ser validado e mensagens devem aparecer para o usuário;

A listagem de itens deve vir do localStorage ou de um JSON Server.

### Features adicionais
- Botão de Like
- Data e hora da última vez visualizado
- Se as imagens não forem fornecidas, uma padrão será mostrada (e salva)

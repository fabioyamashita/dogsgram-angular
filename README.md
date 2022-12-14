# Dogsgram

Dogsgram é um CRUD criado em Angular como um projeto final do  Módulo 10 - Angular I da Let's Code - Turma 853 | Web Full Stack.

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

<hr>

### Principal

Desenvolver uma aplicação em angular que permita Criar, Atualizar, Deletar e Visualizar itens dentro de um tema escolhido por você (não pode ser o mesmo de sala de aula);

Um pop-up deve ser aberto ao clicar tanto no botão de edição, quanto no de deleção de um item;

- Visualizando os itens  
  
![dogsgram-list](https://user-images.githubusercontent.com/98363297/207473989-6df11c6e-909d-45a9-99f1-d2e6ca8ec8fa.gif)

- Criando um item  

![dogsgram-create](https://user-images.githubusercontent.com/98363297/207473998-1f1e1a4a-f8bd-4f25-8ad5-053817a99ce7.gif)

- Atualizando um item + Pop-up de edição  

![dogsgram-update](https://user-images.githubusercontent.com/98363297/207474777-85ee8a04-77b7-4cae-b44b-7d06207efa40.gif)

- Deletando um item (Permitir a exclusão de um item através do menu de listagem) + Pop-up de deleção  

![dogsgram-delete](https://user-images.githubusercontent.com/98363297/207474793-42c5ecc5-0d51-4034-bb95-83dab9dd5189.gif)

- Criar as rotas para Criar e Visualizar a listagem de itens;
- Possuir um header para acesso a cada rota (o header deve ser marcado caso a rota esteja ativa);  

![dogsgram-routes](https://user-images.githubusercontent.com/98363297/207476238-4991fd34-b420-484d-a905-f287956d6b5e.gif)

<hr>

### Extra!

O formulário deve ser validado e mensagens devem aparecer para o usuário;  

![dogsgram-input-verification](https://user-images.githubusercontent.com/98363297/207476526-509c85dc-5319-4d15-b41e-4950e5643c1d.gif)

A listagem de itens deve vir do localStorage ou de um JSON Server.
- Foi utilizado o JSON Server como o Back-End da aplicação.

<hr>

### Features adicionais
- Botão de Like  

![dogsgram-like](https://user-images.githubusercontent.com/98363297/207476623-d17b42e1-da0d-4410-8f41-122e9fa850fe.gif)

- Data e hora da última vez visualizado  

![dogsgram-last-seen](https://user-images.githubusercontent.com/98363297/207476658-f10ef347-05b2-4f93-b8e9-66bd671593d8.gif)

- Se as imagens não forem fornecidas, uma padrão será mostrada (e salva)  

![dogsgram-create-nopic](https://user-images.githubusercontent.com/98363297/207476673-71e475af-8497-4597-8b0c-52a344d7b753.gif)

- Página 404 personalizada, caso a rota não seja encontrada  

![dogsgram-404](https://user-images.githubusercontent.com/98363297/207477758-1891f647-2c17-44b2-9921-da77aace5e76.gif)


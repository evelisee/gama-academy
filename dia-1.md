

# Dia 1

## Configuração de ambiente

 1. Instale globalmente o node
 2.  Verifique a versão que foi instalada via CLI
 3. Instale globalmente a CLI do Angular 
 4. Verifique a versão que foi instalada via CLI 
 5. Via CLI do angular, inicie um projeto novo
 6.  Rode a aplicação no servidor local

## Componentizando

 1. Crie um component através da CLI 
 2. Mostre o component criado na página

## Usando CSS

 1. Insira o css do material theme na aplicação toda ([Link do css](https://code.getmdl.io/1.3.0/material.indigo-red.min.css))
 2. No component raiz, crie um botão customizado com os estilos do material
  ```html
  <button class="mdl-button mdl-js-button mdl-button--fab mdl-button--colored">
    <i class="material-icons">add</i>
  </button>
  ```
 3. Ainda no component raiz da aplicação, crie um formulário básico
  ```html
    <input type="email" />
    <input type="password" />
    <button>Entrar</button>
  ```
 4. Mude a cor do botão para vermelho

## Interpolação

 1. Defina um valor na classe `AppComponent` que seja uma `string` qualquer e exiba seu valor na página 
 2. Mostre o resultado da soma de dois números na página

## Utilizando o data binding

 1. Faça o botão de entrar exibir qualquer texto no console do navegador ao ser clicado
 2. Faça o input de email desaparecer de acordo com uma variável setada para true na classe
 3. Adicione uma classe **dinamicamente** no botão entrar, onde sua fonte fique com 16px ao iniciar a página


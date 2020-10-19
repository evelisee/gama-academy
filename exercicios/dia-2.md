
# Dia 2

## Ambiente

 1. Via CLI do angular, inicie um projeto novo
 2. Rode a aplicação no servidor local

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

 ## Property binding

 1. Deixe o botão do formulário antério desabilitado de acordo com uma propriedade da classe com valor false.

## Utilizando o data binding

 1. Faça o botão de entrar exibir qualquer texto no console do navegador ao ser clicado
 2. Mostr um console quando valores forem inseridos no campo email do formulário.

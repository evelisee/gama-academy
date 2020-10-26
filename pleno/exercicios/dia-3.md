# Dia 3

## Organização do projeto

Agora que sabemos o conceito de arquitetura, vamos melhorar nossa aplicação. O que temos até o momento são components jogados e o ideal é utilizar uma arquitetura definida.

1. Siga a arquitetura abaixo e mude a forma como o seu projeto está: (Dica: use a CLI para criar os components nas repectivas pastas)
```
├── src  
│   ├── app         
│   │   ├── pages         
│   │   |   ├── home     (component)   
│   │   |   ├── ataque    (component) 
│   │   |   └── cadastro    (component) 
│   │   ├── shared     
│   │   |   ├── components
│   │   |   |   └──header  (component) 
│   │   |   ├── models
│   │   |   └── directives
│   │   ├── core
│   │   |   ├── services
│   └── ...  
└── ...
```

2. Link na **aplicação toda** o script do material light angular
```js
<script defer src="https://code.getmdl.io/1.3.0/material.min.js"></script>
```
3. No component de header, copie o código do Fixed header [link da documentação](https://getmdl.io/components/index.html#layout-section)
3. Utilize seu component de header no `app.component.html`

## Módulos

1. Crie o módulo de shared na pasta shared via CLI
2. Importe o component HeaderComponent
3. Exporte o component HeaderComponent
4. Importe o component Shared em AppModule

## Conteúdo dentro do component

1. Faça com que um texto qualquer apareça dentro da página (logo após a barra de navegar)
2. Faça com que o component de lista com descrição apareça dentro da página [Component](https://getmdl.io/components/index.html#lists-section)

## NgClass

1. Ao clicar na estrela, faça com que a palavra "favoritado" apareça do lado

## NgClick

1. Na mesma página, crie um layout com o título Ataques
2. Crie um botão d20
3. Ao clicar no d20, faça mostrar na tela um número random de 1 a 20
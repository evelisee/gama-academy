# Dia 5
 
## Lazy Load

1. Separe os módulos das rotas utilizando o lazyloading 'loadChildren'

## Guard

1. Crie uma validação na rota home utilizando os guards


## Input

1. Crie um component de card-personagem com o seguinte html:

```html
<div class="demo-card-square mdl-card mdl-shadow--2dp">
    <div class="mdl-card__title mdl-card--expand">
      <h2 class="mdl-card__title-text">Nome</h2>
    </div>
    <div class="mdl-card__supporting-text">
      <p>Classe</p>
      <p>Raça</p>
      <p>Nível</p>
    </div>
    <div class="mdl-card__actions mdl-card--border">
      <a class="mdl-button mdl-button--colored mdl-js-button mdl-js-ripple-effect">
        Editar
      </a>
    </div>
  </div>
```

2. Atualize o css desse component com as seguintes classes:

```css
.demo-card-square.mdl-card {
    width: 320px;
    height: 320px;
}
.demo-card-square > .mdl-card__title {
    color: #fff;
    background: #46B6AC;
}
```

3. Na página de cadastro, faça com que os valores inseridos no formulário apareçam no card de Perfil (no component card-personagem)

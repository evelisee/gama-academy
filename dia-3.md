
# Dia 3

## Validação

 1. Faça com que o botão de entrar fique desabilitado quando o formulário for inválido
 2. Adicione uma mensagem custom no campo para quando o campo estiver inválido:
```html
<span class="error-msg" [ngClass]="{'is-invalid': form.invalid}">
	Preencha um email! 
</span>
```

## Roteamento

 1. Mova o formulário criado dentro do AppComponent para um novo component dentro da pasta pages `(src/app/pages/login/login.component.ts)`
 2. Mova a listagem de emails criada anteriormente para um novo component dentro da pasta pages chamada Caixa de Entrada
`(src/app/pages/caixa-de-entrada/caixa-de-entrada.component.ts)`
 
 3. Crie o arquivo de rotas
 4. Aponte as respectivas rotas para os componentes
>  ex.: 
>
>  'login' -> LoginComponent
>
>  'inbox' -> CaixaDeEntradaComponent


## Rotas vazias

 1. Configure para que qualquer rota além das existentes sejam redirecionadas para a página de `Login`

## Pipes

 1. Utilize o pipe do angular para transformar uma data [timestamp](https://hkotsubo.github.io/blog/2019-05-02/o-que-e-timestamp) para o padrão 12/05/2020 (dd/MM/yyyy)
 2. Crie um Pipe para adicionar a palavra `Importante` na frente do assunto dos emails (CaixaDeEntrada) 




  

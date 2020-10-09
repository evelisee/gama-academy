
# Dia 2

## Loop no template

 1. Usando como base o objeto abaixo, crie um loop no html do component `AppComponent`

```json
[
	{
	  "from":  "Maria  Luiza",
	  "subject":  "Vaga na Accenture",
	  "content": "Bom dia Maria,estou escrevendo para te informar que você passou no processo seletivo da Accenture."
	},
	{
	  "from": "Casas Bahia",
	  "subject": "Ar condicionado em promoção!",
	  "content": "Olha só o que as Casas Bahia preparou para você!"
	},
	{
	  "from": "Nubank só que não",
	  "subject": "Fatura em atraso",
	  "content": "Verifique os dados do seu cartão e mande email para a gente!"
	}
]
```
## Formulários 

 1. No formulário criado dentro do AppComponent, utilize o `ngModel` e mostre os valores na view conforme o usuário digitar no campo de email.
 2.  Exiba uma mensagem de erro caso o campo não esteja preenchido

## Roteamento

 1. Mova o formulário criado dentro do AppComponent para um novo component dentro da pasta pages `(src/app/pages/login/login.component.ts)`
 2. Mova a listagem de emails criada anteriormente para um novo component dentro da pasta pages chamada Caixa de Entrada
`(src/app/pages/caixa-de-entrada/caixa-de-entrada.component.ts)`
 
 3. Crie o arquivo de rotas
 4. Aponte as respectivas rotas para os componentes
>  ex.: 
>
>  /login -> LoginComponent
>
>  /inbox -> CaixaDeEntradaComponent

  

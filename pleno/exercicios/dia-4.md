# Dia 4

## Event

1. Adicione um campo de input com o placeholder pesquisar na página
2. Faça aparecer na página o que for digitado no input em tempo real
3. Adicione um formulário na página com os campos (utilize o layout do material light):
- Nome (text)
- Raça (text)(Anão, Humano, Orc...)
- Classe (text)(Bárbaro, Mago, Monge, Paladino...)
- Nível (número)
- Telefone do jogador
- Botão de salvar

2. Mostre os valores no template de cada campo

##  NgFor

1.  No component de lista, faça  um loop com os seguintes dados
```json
[
    {
        "classe":  "Bárbaro",
        "descricao": "A fierce warrior of primitive background who can enter a battle rage"
    },
    {
        "classe":  "Bardo",
        "descricao": "An inspiring magician whose power echoes the music of creation"
    },
    {
        "classe":  "Paladino",
        "descricao": "A holy warrior bound to a sacred oath"
    },
    {
        "classe":  "Mago",
        "descricao": "A scholarly magic-user capable of manipulating the structures of reality"
    },
    {
        "classe":  "Druída",
        "descricao": "A priest of the Old Faith, wielding the powers of nature and adopting animal forms"
    }
]
```
2. Crie uma regra onde o clique na estrela mostre a palavra favoritado apenas para o item da linha.
3. Aprimore essa regra e faça com que a estrela mude de cor quando for favoritado

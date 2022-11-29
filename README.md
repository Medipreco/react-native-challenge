# Processo Seletivo Medipreço - React Native

Muito obrigado pelo interesse em fazer parte de nosso time da Medipreço!
O objetivo dessa parte do processo é conhecer mais sobre suas habilidades técnicas, assim saberemos em quais desafios você pode melhor se encaixar e quais gaps(se houverem) podem ser trabalhados juntos ao time caso você seja selecionado.

## Objetivo do projeto

Implementar um **app** que consuma a PokéAPI(https://pokeapi.co/) utilizando **React Native**.

## Protótipo:

O protótipo do app a ser seguido encontra-se neste [Figma](https://www.figma.com/file/Sj1JuLgfekcY3I2WeimUyl/Desafio-t%C3%A9cnico-front-end-mobile?node-id=0%3A1&t=QI2NzJo7oM4dMyeK-1). Este protótipo é apenas uma base para que você possa seguir, mas fique a vontade para inovar.

## Features:
As features que desejamos que você realize são:

- Listagem de cartas de Pokemon
- Pesquisa por cartas de Pokemon
- Ver Detalhes de uma carta

## Listagem de cartas
Para a listagem, utilize o endpoint de geração (utilize a geração 1).

```
`${baseUrl}/generation/1`
```

A pesquisa pode ser feita localmente, na lista recebida por essa api.

Note que a PokéAPI possui paginação, caso queira se utilizar dela (Opcional)

#### Imagem do pokemon
Para mostrar a imagem de um pokemon, utilize a URL abaixo:

```
`https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/dream-world/${id}.svg`
```

Sendo **id** o id do pokemon.

#### Cor do pokemon
Para mostrar a cor do pokemon, utilize o endpoint

```
`${baseUrl}/pokemon-species/${id}/`
```
Sendo **id** o id do pokemon.
## Detalhes de um pokemon

Na tela de detalhes de um pokemon, utilize o seguinte endpoint para obter os detalhes de um pokemon:

```
`${baseUrl}/pokemon/${id}/`
```
Sendo **id** o id do pokemon.

## Diferenciais:
- Arquitetura limpa e bem definida
- Listagem otimizada
- Boa separação de componentes e funções
- Gitflow limpo, commits bem criados e concisos
- Desenvolva seus próprios componentes e mostre do que você é capaz, queremos ver sua lógica de programação e sua capacidade de resolver problemas.

## Dúvidas

Qualquer dúvida que tiver, não exite em perguntar! Pode mandar email para guilherme.banci@medipreco.com.br ou mandar mensagem no meu [Linkedin](https://www.linkedin.com/in/gbanci/).

### Boa Sorte!
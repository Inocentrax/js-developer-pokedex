# Pokédex com JavaScript

Pokédex em HTML, CSS e JavaScript que consulta a PokéAPI, apresenta tipos e imagens e pagina os primeiros 151 Pokémon.

**Status:** Projeto de estudo.

[← Catálogo de projetos e estudos](https://github.com/Inocentrax/portfolio-dados)

---

Uma interface para explorar Pokémon, construída durante a trilha JavaScript Developer da DIO. A aplicação consulta a PokéAPI e mostra nome, número, tipos e imagem.

## O que está implementado

- Carregamento inicial de 10 Pokémon.
- Botão para carregar os próximos registros, até o limite de 151.
- Cartões com cor por tipo e imagem.

## Como executar

Abra `index.html` no navegador ou use um servidor local, como a extensão Live Server do VS Code. É necessário acesso à internet para consultar a API e carregar as imagens. Não há etapa de build.

## Mapa do código

| Arquivo | Responsabilidade |
|---|---|
| [index.html](index.html) | Estrutura da página |
| [main.js](assets/js/main.js) | Renderização e paginação |
| [poke-api.js](assets/js/poke-api.js) | Consulta e conversão dos dados da API |
| [pokemon-model.js](assets/js/pokemon-model.js) | Modelo de dados |
| [CSS](assets/css/) | Layout e cores |

## Evolução

- [ ] Exibir estado de carregamento e falha de rede.
- [ ] Evitar cliques concorrentes no botão de paginação.
- [ ] Adicionar busca e detalhes de cada Pokémon.

## Créditos

Estudo desenvolvido na trilha da DIO; dados e imagens consultados pela PokéAPI.

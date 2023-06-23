# Documentação do Projeto "Pokedex"

## Introdução

A Pokedex é uma página da web que exibe informações sobre Pokemons em uma lista contínua, carregando mais Pokemons à medida que o usuário rola a página. O projeto utiliza JavaScript puro para criar elementos HTML dinamicamente e se baseia na biblioteca DOMPurify para garantir que as informações da API sejam purificadas antes de serem exibidas.

## Funcionalidades Principais

- Exibição de Pokemons: A página exibe os Pokemons em uma lista contínua, renderizando 15 Pokemons por vez.
- Carregamento sob Demanda: À medida que o usuário se aproxima do final da lista, mais 5 Pokemons são carregados automaticamente.
- Purificação de Dados: As informações obtidas da API são purificadas usando a biblioteca DOMPurify para garantir a segurança e integridade dos dados exibidos.

## Configuração do Ambiente

Para executar o projeto localmente, siga as etapas abaixo:

1. Clone o repositório do projeto Pokedex do GitHub:
- git clone https://github.com/seu-usuario/pokedex.git
2. Navegue até o diretório do projeto:
- cd pokedex
3. Abra o arquivo index.html em um navegador da web para visualizar a página.

## Bibliotecas Utilizadas

O projeto Pokedex utiliza as seguintes bibliotecas:

- DOMPurify: Biblioteca utilizada para purificar as informações obtidas da API e evitar ataques de Cross-Site Scripting (XSS).

## Estrutura do Código

O código do projeto está organizado da seguinte forma:

pokedex/<br>
├── index.html<br>
├── script.js<br>
├── style.css<br>
└── assets/<br>
....└── img/<br>
........├── pokemon1.jpg<br>
........├── pokemon2.jpg<br>
........└── pokemon3.jpg



- `index.html`: O arquivo HTML principal que contém a estrutura básica da página e inclui os scripts e estilos necessários.
- `script.js`: O arquivo JavaScript que contém a lógica do projeto, incluindo a renderização dos Pokémons e o carregamento sob demanda.
- `style.css`: O arquivo CSS que contém os estilos para a página.
- `assets/img/`: A pasta `assets` é adicionada no diretório raiz do projeto e dentro dela está a pasta `img`, que contém as imagens dos Pokémons utilizadas na página. Certifique-se de colocar as imagens reais nessa pasta para que possam ser exibidas corretamente no projeto.

## Uso da API

O projeto Pokedex consome uma API externa para obter informações sobre os Pokémons. A API utilizada é a "pokeapi.co". O código JavaScript contém as requisições HTTP necessárias para obter os dados dos Pokémons e utilizá-los na renderização da página.

## Considerações Finais

A Pokedex é um projeto interativo e responsivo que oferece aos usuários uma experiência contínua ao explorar informações sobre os Pokémons. Ao utilizar JavaScript puro e a biblioteca DOMPurify, o projeto prioriza a segurança e a qualidade dos dados exibidos na página.



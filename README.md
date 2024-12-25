# Projeto Rick and Morty

## Descrição

Este projeto é uma aplicação web interativa que exibe informações detalhadas sobre os personagens da popular série de TV "Rick and Morty". A aplicação consome dados da API pública de Rick and Morty e utiliza tecnologias modernas como HTML5, Javascript e React para proporcionar uma experiência de usuário dinâmica e responsiva. O objetivo é criar uma plataforma onde os fãs possam explorar e descobrir informações sobre seus personagens favoritos de forma intuitiva e atraente. 

## Processo de Desenvolvimento:
O desenvolvimento da aplicação começou com a definição da estrutura dos componentes em React para garantir uma organização modular e reutilizável. Em seguida, implementei as chamadas à API utilizando fetch, garantindo que os dados dos personagens fossem carregados e exibidos corretamente.

Para a estilização, usei CSS3, garantindo que a interface fosse atraente e responsiva. Testei extensivamente a aplicação em diferentes dispositivos para garantir que a experiência do usuário fosse consistente.

## Problemas Encontrados e Soluções:

### Desempenho das Requisições à API:

 - Problema: As requisições à API estavam demorando mais do que o esperado.

 - Solução: Implementei caching no lado do cliente e usei técnicas de lazy loading para carregar os dados de forma mais eficiente.

### Gerenciamento de Estado:

 - Problema: O gerenciamento de estado estava ficando complexo com o aumento do número de personagens.

 - Solução: Utilizei Context API do React para gerenciar o estado global de forma mais eficiente.

### Responsividade da Interface:

 - Problema: A interface não estava se adaptando corretamente em alguns dispositivos móveis.

 - Solução: Ajustei os estilos CSS utilizando media queries para garantir que o site fosse totalmente responsivo.

## Tecnologias utilizadas

[![My Skills](https://skillicons.dev/icons?i=html,css,javascript,react,nodejs,npm)](https://skillicons.dev)

## Funcionalidades

- Listagem de Personagens: Exibe uma lista de personagens da série
- Detalhes dos Personagens: Fornece informações detalhadas sobre cada personagem, incluindo nome, status, espécie, gênero, e uma imagem.
- Navegação Responsiva: O site é totalmente responsivo e funciona bem em dispositivos móveis e desktops.

## Pré Requisitos

- Node.JS e npm (node package manager)
- Editor de codigo de preferência o VSCode
- navegador de sua preferência

## Como rodar localmente

- Clonar o Repositório:

``` sh
git clone https://github.com/Davi504/projeto_rick_and_morty.git
cd projeto_rick_and_morty
```

- instalar dependências:

``` sh
 npm install
```

- iniciar servidor:

``` sh
npm run dev
```

Isso iniciará o servidor de desenvolvimento, configurado para rodar com o script dev, e abrirá seu navegador padrão em http://localhost:3000, ou na porta especificada no seu arquivo de configuração.

## Licença 

Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.



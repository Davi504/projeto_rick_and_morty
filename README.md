# Projeto Rick and Morty

## Descrição
Este projeto é uma aplicação web interativa que exibe informações detalhadas sobre os personagens da popular série de TV "Rick and Morty". A aplicação consome dados da API pública de Rick and Morty e utiliza tecnologias modernas como HTML5, Javascript e React para proporcionar uma experiência de usuário dinâmica e responsiva. O objetivo é criar uma plataforma onde os fãs possam explorar e descobrir informações sobre seus personagens favoritos de forma intuitiva e atraente.

## Link da aplicação rodando

[Link do video](https://youtu.be/yRZ6b47O1cg?si=HlXCJfzvIoRaawkp)


### Objetivo
O principal objetivo deste projeto é oferecer uma plataforma visual e intuitiva para os fãs da série "Rick and Morty". Queremos permitir que os usuários possam explorar facilmente as informações dos personagens, conhecendo detalhes e curiosidades de forma prática e divertida.

### Público-alvo
Este projeto é destinado a todos os fãs da série "Rick and Morty", bem como a qualquer pessoa interessada em explorar conteúdos sobre personagens de séries de TV. Além disso, pode ser útil para desenvolvedores que queiram entender como consumir APIs públicas e integrar esses dados em aplicações React.

### Futuras Melhorias
- Implementar sistema de busca avançada por personagens.
- Adicionar filtros por espécies, status e gênero.
- Melhorar o layout da interface do usuário.
- Implementar animações para uma experiência de usuário mais rica.
- Permitir que os usuários possam salvar seus personagens favoritos.

## Processo de Desenvolvimento
O desenvolvimento da aplicação começou com a definição da estrutura dos componentes em React para garantir uma organização modular e reutilizável. Em seguida, implementei as chamadas à API utilizando fetch, garantindo que os dados dos personagens fossem carregados e exibidos corretamente.

Para a estilização, usei CSS3, garantindo que a interface fosse atraente e responsiva. Testei extensivamente a aplicação em diferentes dispositivos para garantir que a experiência do usuário fosse consistente.

## Problemas Encontrados e Soluções

### Desempenho das Requisições à API
- **Problema**: As requisições à API estavam demorando mais do que o esperado.
- **Solução**: Implementei caching no lado do cliente e usei técnicas de lazy loading para carregar os dados de forma mais eficiente.

### Gerenciamento de Estado
- **Problema**: O gerenciamento de estado estava ficando complexo com o aumento do número de personagens.
- **Solução**: Utilizei Context API do React para gerenciar o estado global de forma mais eficiente.

### Responsividade da Interface
- **Problema**: A interface não estava se adaptando corretamente em alguns dispositivos móveis.
- **Solução**: Ajustei os estilos CSS utilizando media queries para garantir que o site fosse totalmente responsivo.

## Tecnologias Utilizadas
[![My Skills](https://skillicons.dev/icons?i=html,css,javascript,react,nodejs,npm)](https://skillicons.dev)

## Funcionalidades
- **Listagem de Personagens**: Exibe uma lista de personagens da série.
- **Detalhes dos Personagens**: Fornece informações detalhadas sobre cada personagem, incluindo nome, status, espécie, gênero e uma imagem.
- **Navegação Responsiva**: O site é totalmente responsivo e funciona bem em dispositivos móveis e desktops.

## Pré-requisitos
- Node.JS e npm (node package manager)
- Editor de código, de preferência o VSCode
- Navegador de sua preferência

## Como Rodar Localmente
1. **Clonar o Repositório**:
    ```sh
    git clone https://github.com/Davi504/projeto_rick_and_morty.git
    cd projeto_rick_and_morty
    ```

2. **Instalar Dependências**:
    ```sh
    npm install
    ```

3. **Iniciar Servidor**:
    ```sh
    npm run dev
    ```

Isso iniciará o servidor de desenvolvimento, configurado para rodar com o script dev, e abrirá seu navegador padrão em [http://localhost:3000](http://localhost:3000), ou na porta especificada no seu arquivo de configuração.

## Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

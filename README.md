# Go Shoes Hooks

Projeto e-commerce de vendas de tênis, desenvolvido em ReactJS aplicando Arquitetura Flux com Redux para demonstrar a funcionalidade dessa Arquitetura e com suporte ao Hooks.

## O que é [Hooks](https://pt-br.reactjs.org/docs/hooks-intro.html)?

Hooks são uma nova adição ao React 16.8. Eles permitem que você use o state e outros recursos do React sem escrever uma classe.

### Sem Quebras de Compatibilidade

##### Antes de continuar, note que Hooks são:

Completamente opcionais. Você pode experimentar Hooks em alguns componentes sem reescrever nenhum código existente. Mas você não tem que aprender ou usar Hooks agora se não quiser.
100% retrocompatíveis. Hooks não possuem nenhuma quebra de compatibilidade.
Disponível agora. Hooks estão disponíveis no release v16.8.0.
Não temos planos de remover classes do React. Você pode aprender mais sobre a estratégia de adoção gradual para Hooks na seção inferior desta página.

Hooks não substituem seu conhecimento dos conceitos de React. Ao invés disso, Hooks provêem uma API mais direta para os conceitos de React que você já conhece: props, state, context, refs e ciclo de vida. Como iremos mostrar em breve, Hooks também oferecem uma poderosa nova forma de combiná-los.

Se você só quiser começar a aprender Hooks, sinta-se livre para pular direto para a próxima página! Você também pode continuar lendo esta página para aprender mais sobre o porquê de estarmos adicionando Hooks e como nós iremos começar a usá-los sem reescrever nossas aplicações.

## O que é [Redux](https://redux.js.org/)?

- Biblioteca que implementa Arquitetura Flux;
- Controle de estados globais;
- Quando utilizar o Redux?
  - Quando meu estado tem mais de um “dono”
  - Quando meu estado é manipulado por mais componentes
  - Quando as ações do usuário causam efeitos colaterais nos dados
  - Exemplos: Carrinho de compras, dados do usuário, player de música, etc;

### Ferramenta de API FAKE

Foi utilizado como API [JSON Server](https://github.com/typicode/json-server) uma biblioteca que permite utilizar um arquivo JSON e criar uma API a partir desse arquivo.

#### JSON Server

Para utilizar no terminal ou prompt de comando dentro do diretório do projeto digite:

`json-server server.json -p 3333 -w`

onde:

- `json-server` comando para executar a biblioteca
- `server.json` parametro passando qual arquivo possui a estrutura JSON da API
- `-p 3333` parametro que passa qual porta o JSON Server será inicializado.
- `-w` parametro que ficará observando alteração no arquivo JSON e sendo assim quando houver, irá ser restartado o JSON Server

### Ferramentas de análise de código estático:

- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)

### Style Guide utilizada:

- [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)

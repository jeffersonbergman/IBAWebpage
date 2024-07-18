# IBAProject

Este projeto foi gerado com [Svelte](https://svelte.dev).

## Servidor de Desenvolvimento

Execute `npm run dev` para iniciar o servidor de desenvolvimento. Navegue até `http://localhost:5173/`. A aplicação será recarregada automaticamente se você alterar qualquer um dos arquivos de origem.

## Estrutura do Código

Os principais arquivos e pastas do projeto são:
- `src/`: Contém os arquivos fonte da aplicação.
  - `App.svelte`: Componente raiz da aplicação.
  - `routes/`: Contém os componentes das rotas principais.
  - `components/`: Contém os componentes reutilizáveis da aplicação.
- `public/`: Contém arquivos estáticos públicos.

## Criação de Componentes

Para criar um novo componente, adicione um arquivo `.svelte` na pasta apropriada dentro de `src/` (como `components` ou `routes`).

## Build

Execute `npm run build` para construir o projeto. Os artefatos de build serão armazenados no diretório `public/build`.

## Executando Testes Unitários

Você pode configurar e executar testes unitários utilizando bibliotecas como `Jest` ou `Testing Library` para Svelte. Para instalar `Testing Library`:

```sh
npm install --save-dev @testing-library/svelte @testing-library/jest-dom

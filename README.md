# Teste React

Projeto de estudo criado com React e Vite para praticar componentes, JSX, interpolação de valores e passagem de props. A página principal renderiza quatro instâncias do componente `Pratica`.

## Requisitos

- Node.js e npm instalados. Use uma versão do Node.js compatível com o Vite definido em `package.json`.

## Como executar

```bash
npm install
npm run dev
```

Abra no navegador o endereço exibido pelo Vite no terminal.

## Comandos disponíveis

| Comando | Descrição |
| --- | --- |
| `npm run dev` | Inicia o servidor de desenvolvimento. |
| `npm run build` | Gera a versão de produção em `dist/`. |
| `npm run preview` | Exibe localmente a versão gerada pelo build. |
| `npm run lint` | Executa a verificação do ESLint. |

## Estrutura principal

- `src/App.jsx`: renderiza o componente `Pratica` quatro vezes.
- `src/Pratica.jsx`: contém o componente usado no exercício.
- `src/main.jsx`: monta a aplicação no elemento `root`.
- `vite.config.js`: configura o Vite e o React Compiler.

## Estado atual

Este repositório é um exercício em desenvolvimento. O componente `Pratica` recebe a prop `que`, mas ainda não a utiliza na interface. O botão não tem texto e seu manipulador chama `setTexto`, enquanto a função de atualização do estado foi declarada como `SetTexto`; por isso, clicar nele causa um erro. A imagem também usa um caminho relativo ao código-fonte que pode não funcionar na aplicação servida ou no build.

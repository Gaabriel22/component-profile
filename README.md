# Component Profile

Este é um exercício desenvolvido durante o módulo de Fundamentos de React do curso de Desenvolvedor Fullstack JavaScript da OneBitCode.

## Descrição

Este exercício consiste na criação de um componente React chamado `Profile`, que exibe informações de perfil de usuário, incluindo avatar, nome, biografia, email, telefone e links sociais. Além disso, o componente inclui um botão para seguir o usuário, com funcionalidade de alternar entre "Follow" e "Following".

## Componentes

O exercício consiste nos seguintes componentes:

- `App`: Componente principal que renderiza o componente `Profile`.
- `Profile`: Componente que exibe as informações de perfil do usuário.
- `ProfileSection`: Componente utilizado pelo `Profile` para exibir seções específicas do perfil.
- `Title`: Componente utilizado pelo `Profile` para exibir o título do perfil.
- `LinkButton`: Componente utilizado pelo `Profile` para exibir links sociais.

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

- **src/**
  - **components/**
    - **Profile/**
      - `index.jsx`
      - `styles.module.css`
    - **ProfileSection/**
      - `index.jsx`
      - `styles.module.css`
    - **Title/**
      - `index.jsx`
      - `styles.module.css`
    - **LinkButton/**
      - `index.jsx`
      - `styles.module.css`
  - `App.jsx`
  - `main.jsx`
- **styles/**
  - `globals.css`

## Como Executar

Para executar o projeto localmente, siga estas etapas:

1. Clone este repositório.
2. Instale as dependências do projeto usando `npm install`.
3. Execute o projeto usando `npm run dev` (ou o comando que você normalmente usa para iniciar o servidor de desenvolvimento).
4. Abra o navegador e acesse o endereço fornecido pelo seu ambiente de desenvolvimento para visualizar o aplicativo.

## Autor

Este exercício foi desenvolvido como parte do curso de Desenvolvedor Fullstack JavaScript da OneBitCode.

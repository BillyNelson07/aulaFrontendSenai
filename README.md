# React Menu TS App

Este é um projeto de aula do SENAI para demonstrar o uso de navegação em uma aplicação React com TypeScript. O aplicativo inclui um menu lateral responsivo, barra de navegação superior e roteamento entre páginas usando React Router.

## Funcionalidades

- **Menu Lateral**: Abre e fecha com um botão, contendo links para todas as páginas.
- **Barra Superior**: Navegação rápida e botão para alternar o menu.
- **Páginas**:
  - Início: Tela inicial com descrição do projeto.
  - Sobre: Informações sobre o aplicativo.
  - Serviços: Lista de serviços oferecidos.
  - Contato: Formulário ou informações de contato.
  - Perfil: Página de perfil do usuário.
  - Disciplina: Página relacionada à disciplina do curso.
- **Roteamento**: Implementado com React Router DOM para navegação SPA (Single Page Application).

## Tecnologias Utilizadas

- **React**: Biblioteca para construção da interface.
- **TypeScript**: Superset do JavaScript com tipagem estática.
- **Vite**: Ferramenta de build rápida para desenvolvimento.
- **React Router DOM**: Para gerenciamento de rotas.
- **ESLint**: Para linting e qualidade de código.

## Estrutura do Projeto

```
react-menu-ts-app/
├── public/                 # Arquivos estáticos
├── src/
│   ├── components/         # Componentes reutilizáveis
│   │   ├── Layout.tsx      # Layout principal com sidebar e top nav
│   │   ├── SidebarMenu.tsx # Menu lateral
│   │   └── TopNav.tsx      # Barra de navegação superior
│   ├── pages/              # Páginas da aplicação
│   │   ├── HomePage.tsx
│   │   ├── SobrePage.tsx
│   │   ├── ServicosPage.tsx
│   │   ├── ContatoPage.tsx
│   │   ├── PerfilPage.tsx
│   │   └── DisciplinaPage.tsx
│   ├── App.tsx             # Componente principal com rotas
│   ├── main.tsx            # Ponto de entrada
│   └── styles.css          # Estilos globais
├── package.json            # Dependências e scripts
├── vite.config.ts          # Configuração do Vite
└── tsconfig.json           # Configuração do TypeScript

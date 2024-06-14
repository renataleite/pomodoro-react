# Pomodoro React

Pomodoro React é uma aplicação web desenvolvida para ajudar na gestão de tempo utilizando a técnica Pomodoro. A aplicação permite que os usuários definam projetos, tempos de trabalho, e acompanha o histórico de sessões de trabalho.

## Tecnologias Utilizadas

- React
- TypeScript
- Vite
- Styled-Components
- React Hook Form
- Date-fns
- Phosphor-React
- Zod

## Funcionalidades

### Timer Pomodoro

- **Descrição**: Permite iniciar, pausar e resetar o timer Pomodoro.
- **Entrada do Usuário**: Nome do projeto e duração em minutos.
- **Interface**: Contador visual com botões de controle.

### Histórico de Sessões

- **Descrição**: Exibe o histórico das sessões de trabalho, incluindo nome do projeto, duração, início e status.
- **Interface**: Tabela com informações das sessões.

## Instalação e Execução

### Pré-requisitos

- Node.js
- npm ou yarn

### Passos para Configuração

1. Clone o repositório.
   ```bash
   git clone https://github.com/seu-usuario/pomodoro-react.git
   cd pomodoro-react
   ```

2. Instale as dependências.
   ```bash
   npm install
   # ou
   yarn install
   ```

3. Inicie o servidor de desenvolvimento.
   ```bash
   npm run dev
   # ou
   yarn dev
   ```

4. Acesse a aplicação no navegador.
   ```url
   http://localhost:3000
   ```

## Estrutura do Projeto

### Dependências

- **@hookform/resolvers**: ^2.9.10
- **date-fns**: ^2.29.3
- **phosphor-react**: ^1.4.1
- **react**: ^18.2.0
- **react-dom**: ^18.2.0
- **react-hook-form**: ^7.41.1
- **react-router-dom**: ^6.6.1
- **styled-components**: ^5.3.6
- **zod**: ^3.20.2

### Dependências de Desenvolvimento

- **@types/react**: ^18.0.17
- **@types/react-dom**: ^18.0.6
- **@types/styled-components**: ^5.1.26
- **@vitejs/plugin-react**: ^2.0.1
- **typescript**: ^4.6.4
- **vite**: ^3.0.7

## Funcionalidades Principais

### Timer

- **Descrição**: Timer visual com controles para iniciar, pausar e resetar o tempo de trabalho.
- **Componentes Utilizados**: React, Styled-Components.

### Histórico

- **Descrição**: Registro das sessões de trabalho completadas.
- **Componentes Utilizados**: React, Styled-Components, Date-fns.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

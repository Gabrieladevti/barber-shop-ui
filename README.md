# Barber Shop UI

**Barber Shop UI** é uma interface de usuário desenvolvida para um sistema de agendamento e gerenciamento de serviços de barbearia. O objetivo do projeto é fornecer uma experiência simples e intuitiva para os clientes, permitindo que agendem horários, visualizem serviços disponíveis, e escolham os barbeiros.

## Funcionalidades

- **Agendamento de serviços**: Permite que os clientes agendem horários para serviços de barbearia.
- **Exibição de serviços**: Lista todos os serviços oferecidos pela barbearia, como corte de cabelo, barba, etc.
- **Escolha de barbeiro**: O cliente pode selecionar o barbeiro de sua preferência.
- **Interface responsiva**: A interface foi projetada para ser acessível em diversos dispositivos, incluindo desktop e mobile.
- **Feedback visual**: Confirmações de agendamento, sucesso ou falha no processo.

## Tecnologias Utilizadas

- **React**: Framework utilizado para criar a interface de usuário.
- **React Router**: Para navegação entre diferentes páginas (ex.: serviços, agendamentos, etc.).
- **Styled-components**: Para estilização dinâmica e modular dos componentes.
- **Axios**: Para fazer requisições HTTP para o backend (se aplicável).
- **Redux (opcional)**: Para gerenciar o estado da aplicação, como o agendamento e seleção de barbeiros.

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

- **src/**: Contém todos os arquivos de código-fonte.
  - **components/**: Componentes reutilizáveis da interface.
  - **pages/**: Páginas principais da aplicação (ex.: Home, Agendamento, Serviços).
  - **styles/**: Arquivos de estilo globais e temas.
  - **services/**: Arquivos para integração com API (se houver).

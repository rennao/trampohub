# 💼 TrampoHub — Sistema Modular de Gestão e Intermediação de Serviços

O **TrampoHub** é uma aplicação web arquitetada sob o conceito de MVP (Minimum Viable Product) voltada para a intermediação e provisionamento de oportunidades de trabalho. O objetivo principal do ecossistema é centralizar o fluxo de conexões profissionais em uma interface segura, performática e de baixa latência.

> ⚠️ **Status:** Em desenvolvimento (Ambiente de Staging). Camada de UI (User Interface) e regras de negócio do client-side concluídas; backend e persistência em fase de integração.

---

## 📁 Arquitetura e Estrutura de Módulos

A aplicação adota separação de conceitos através de componentes modulares em Vanilla JS:

- **Módulo de Autenticação (`login.html` / `cadastro.html`):** Fluxo para novos usuários, focado na validação estrutural de payloads de entrada no front-end.
- **Dashboard Core (`home.html` / `index.html`):** Hub centralizado para o consumo e renderização dinâmica dos blocos de serviços de forma assíncrona.
- **Engine de Mensageria (`chat.html` / `chat.js`):** Componente dinâmico de chat isolado, preparado para a integração de protocolos de comunicação bidirecional.
- **Manipulação de Estado e Dados (`database.js` / `script.js`):** Camada responsável pela escuta de eventos do DOM, ciclo de vida da página e mock lógico de dados.

---

## 🛠️ Stack Tecnológica

- **Frontend:** HTML5 Semântico, CSS3 (Arquitetura de Layout baseada em Flexbox e Variáveis CSS) e JavaScript Assíncrono (ES6+).
- **Ambiente de Execução:** Node.js para gerenciamento do ciclo de dependências.
- **Deploy:** Configuração de redirecionamentos e infraestrutura serverless preparada para distribuição na nuvem (Netlify).

---

## 📈 Roadmap Técnico
- [ ] Implementação de WebSockets (Socket.io) na camada de mensageria para tráfego de dados em tempo real.
- [ ] Integração das rotas de autenticação a um banco de dados relacional (SQLite/PostgreSQL).
- [ ] Implementação de middlewares de segurança (hashing de senhas e JWT) no backend.

---
✉️ **Contato:** rennerfag@gmail.com | Discord: blinbas

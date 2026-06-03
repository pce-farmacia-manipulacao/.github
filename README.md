# Aplicação Web Para Clientes De Farmácias de Manipulação (PCE I)

## 📋 Sobre o Projeto
Este projeto consiste no desenvolvimento de uma aplicação web voltada para clientes de farmácias de manipulação, desenvolvida em parceria com a Product Owner Simone Parisi (Homeofórmula Farmácia & Laboratório). O sistema visa centralizar o histórico de compras, permitir a repetição ágil de pedidos de fórmulas contínuas (já validadas) e oferecer benefícios de fidelidade, promovendo o autoatendimento seguro do cliente e reduzindo custos operacionais da farmácia.

A arquitetura do sistema segue o modelo MVC (Model-View-Controller), garantindo separação de responsabilidades, alta manutenibilidade e total conformidade com a LGPD para a proteção de dados sensíveis de saúde.

---

## 📂 Organização dos Repositórios
Para garantir modularidade e reusabilidade do código, o ecossistema do projeto foi dividido nos seguintes repositórios:

*   **[pce-backend](link_do_repositorio_aqui):** API RESTful desenvolvida em Node.js com Express e banco de dados relacional PostgreSQL. Contém as rotas de autenticação, histórico de compras e regras de negócio.
*   **[pce-frontend](link_do_repositorio_aqui):** Interface de usuário responsiva desenvolvida em React.js, consumindo a API do backend via Axios. Inclui fluxos de login seguro, visualização de histórico e repetição de pedidos.
*   **[pce-modelos-uml](link_do_repositorio_aqui):** Repositório dedicado à engenharia de software e modelagem do sistema, contendo os arquivos de diagramação e protótipos de UX.

---

## 👥 Participantes e Contato
*   **João Victor Gonçalves Correia Evangelista**
    *   📧 E-mail institucional: jvevangelista@unisantos.br
*   **Luiz Alberto Coelho Barbosa**
    *   📧 E-mail institucional: l.alberto@unisantos.br

---
*Projeto desenvolvido como parte do Projeto Comunitário de Extensão (PCE) - Universidade Católica de Santos (UniSantos), 2026.*

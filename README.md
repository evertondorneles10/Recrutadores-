# Portfólio para recrutadores

Este repositório apresenta os projetos que desenvolvi sozinho, do front ao back. O código dos projetos é privado, porque estão em fase de comercialização. Aqui você encontra o que cada um faz, as decisões técnicas e como validar o funcionamento.

**Everton Dorneles Fontoura** · Desenvolvedor full stack em formação (ADS, PUCRS, 6º trimestre) · Campo Bom/RS
[LinkedIn](https://www.linkedin.com/in/everton-dorneles-958a70233) · dev.dorneles@gmail.com

## Como validar os projetos

- **Acesso aos apps:** o link de cada aplicação consta no currículo enviado ao recrutador. Se preferir, peça por e-mail.
- **Código:** privado. Posso apresentar a arquitetura e trechos do código em uma conversa técnica.

---

## Opera Hub

*jun/2026 – atual · publicado, aberto a primeiros usuários*

Plataforma SaaS multiempresa (PWA) para gestão de manutenção e operações. Atende empresas, hotéis, escolas e outros ambientes com manutenção recorrente.

**Destaques**
- Multiempresa: dados e acessos separados por organização.
- Permissões individuais: o gestor define quem pode gerar ordens de serviço e quem pode usar IA.
- Ordem de serviço direcionada a um colaborador específico; a baixa só acontece após vistoria e validação do gestor ou encarregado.
- Controle de SLA de terceirizadas.
- QR Code por ambiente e equipamento, que abre histórico, ordens pendentes e manutenções preventivas e corretivas.
- Dashboard com gráficos, agenda e IA (Gemini) no servidor, com cota por cliente.
- Modo de demonstração que não grava dados permanentes nem consome cota de IA.

**Stack:** React · TypeScript · Node.js · Firebase (Authentication, Firestore) · Render

---

## Aurah Vision

*abr/2026 – atual · publicado, aberto a primeiros usuários*

PWA híbrido de gestão financeira pessoal e familiar, com estrutura preparada para Android via Capacitor.

**Destaques**
- Dashboard com teto orçamentário e histórico de transações com filtros e paginação.
- Consultor financeiro com IA (Gemini no backend), com limite de uso por usuário.
- Lista de compras com busca de estabelecimentos em camadas (IA e mapas, catálogo interno e OpenStreetMap).
- Orçamento familiar com compartilhamento controlado entre membros.
- Painel do desenvolvedor com auditoria e acompanhamento de custos e chamadas de IA.
- Inclui um recurso de segurança pessoal discreto, em fase de testes.

**Stack:** React · TypeScript · Node.js/Express · Firebase (Authentication, Firestore, Storage) · Render

---

## Enigma QA

*em fase final de desenvolvimento*

Ferramenta que testa PWAs, sites e softwares com vários motores e gera relatórios de melhorias e vulnerabilidades.

---

## Nexus

*em desenvolvimento*

Assistente pessoal com IA que se adapta ao estilo de vida do usuário.

---

## Decisões técnicas que valem

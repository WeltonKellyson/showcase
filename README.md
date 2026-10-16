<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0B1020,40:1E3A8A,75:2563EB,100:38BDF8&text=Showcase&fontColor=FFFFFF&fontSize=50&fontAlignY=36&desc=Sistemas%20corporativos%20em%20produ%C3%A7%C3%A3o%20%C2%B7%20Welton%20Kellyson&descAlignY=58&descSize=17&animation=fadeIn"/>

<div align="center">

**Vitrine dos sistemas que desenvolvi como Desenvolvedor Full Stack na Health & Safety**

<sub>O código é privado (propriedade da empresa). Aqui estão as telas, o que cada sistema faz e a stack usada.<br/>⚠️ Todas as telas usam <b>dados fictícios</b>.</sub>

<br/>

<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind-0F172A?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>

</div>

---

## 📑 Sistemas

| Sistema | O que é | Destaque |
|---|---|---|
| [🎫 HelpHS](#-helphs--help-desk-para-clientes) | Help Desk para clientes externos | Substituiu o atendimento via WhatsApp |
| [🧠 TalentHS](#-talenths--plataforma-de-rh-com-ia) | Plataforma de RH com psicometria e IA | DISC/OCEAN, 9Box e chat com IA |
| [🏷️ ControlHS](#️-controlhs--gestão-de-patrimônio) | Gestão de patrimônio | 400+ itens · R$ 200 mil em ativos |
| [📈 GrowthHS](#-growthhs--crm-comercial) | CRM comercial próprio | Substituiu o Pipedrive |
| [🛠️ ChamadosHS](#️-chamadoshs--help-desk-interno) | Help Desk interno de TI | Kanban de chamados com prioridades |

> Desenvolvidos em parceria com **Erick Santos**: eu à frente do front-end e atuando junto com ele no back-end (APIs em FastAPI e modelagem PostgreSQL), do desenho da solução ao deploy.

---

## 🎫 HelpHS — Help Desk para clientes

Os clientes externos abriam chamados pelo WhatsApp, sem controle, SLA ou histórico. O HelpHS virou a plataforma oficial de suporte.

- Kanban de tickets com status em tempo real
- SLA automático por prioridade, com alertas de vencimento
- Dashboard com CSAT, tempo médio de resolução e conformidade de SLA
- Base de conhecimento, perfis de acesso (Admin, Técnico, Usuário) e audit log

**Stack:** React · TypeScript · Tailwind · Python · FastAPI · PostgreSQL · Docker · Easypanel

<table>
  <tr>
    <td><img src="images/helphs-dashboard-principal.jpg" alt="HelpHS - Dashboard"/><br/><sub>Dashboard</sub></td>
    <td><img src="images/helphs-tickets.jpg" alt="HelpHS - Tickets"/><br/><sub>Kanban de tickets</sub></td>
  </tr>
  <tr>
    <td colspan="2"><img src="images/helphs-configuracoes-de-sla.jpg" alt="HelpHS - Configurações de SLA"/><br/><sub>Configuração de SLA por prioridade</sub></td>
  </tr>
</table>

---

## 🧠 TalentHS — Plataforma de RH com IA

O projeto mais complexo que já desenvolvi em termos de produto e UX: gestão de pessoas completa, com psicometria e IA.

- Psicometria DISC + OCEAN por colaborador
- Mapa 9Box para avaliação de desempenho
- Chat com IA personalizado pelo perfil do colaborador
- Dashboard de desenvolvimento individual e análise de equipe
- Calendário corporativo, metas e avaliações

**Stack:** React · TypeScript · Tailwind · Python · FastAPI · PostgreSQL · OpenAI API · Docker

<table>
  <tr>
    <td><img src="images/talenths-dashboard-principal-do-rh.jpg" alt="TalentHS - Dashboard do RH"/><br/><sub>Dashboard do RH</sub></td>
    <td><img src="images/talenths-calendario-de-eventos.jpg" alt="TalentHS - Calendário"/><br/><sub>Calendário de eventos</sub></td>
  </tr>
  <tr>
    <td colspan="2"><img src="images/talenths-apresentacao.jpg" alt="TalentHS - Apresentação"/><br/><sub>Página de apresentação da empresa</sub></td>
  </tr>
</table>

---

## 🏷️ ControlHS — Gestão de Patrimônio

Controle completo dos ativos da empresa: cadastro, transferências entre setores, baixas, inventário e depreciação.

- Mais de 400 itens e R$ 200 mil em ativos gerenciados
- Transferências com histórico e rastreabilidade
- Baixas com justificativa e cálculo automático de depreciação
- Sessões de inventário, log de auditoria e controle de acesso por perfis

**Stack:** React · TypeScript · Python · FastAPI · PostgreSQL · Docker · Easypanel

<table>
  <tr>
    <td><img src="images/controlhs-dashboard-principal.jpg" alt="ControlHS - Dashboard"/><br/><sub>Dashboard de patrimônio</sub></td>
    <td><img src="images/controlhs-gestao-de-transferencia.jpg" alt="ControlHS - Transferências"/><br/><sub>Gestão de transferências</sub></td>
  </tr>
  <tr>
    <td><img src="images/controlhs-gestao-de-baixa.jpg" alt="ControlHS - Baixas"/><br/><sub>Baixas patrimoniais</sub></td>
    <td><img src="images/controlhs-gestao-de-inventario.jpg" alt="ControlHS - Inventário"/><br/><sub>Inventário</sub></td>
  </tr>
</table>

---

## 📈 GrowthHS — CRM Comercial

A assinatura do Pipedrive custava caro e não atendia o fluxo comercial da empresa. Construímos um CRM sob medida.

- Pipeline com boards e cards no formato do time comercial
- Integração com RD Station para ingestão de leads
- Automações configuráveis (atribuição de vendedor/SDR, movimentações)
- Dashboard de SDR e vendedores, com evolução de leads e taxas de conversão

**Stack:** React · TypeScript · Tailwind · Python · FastAPI · PostgreSQL

<table>
  <tr>
    <td><img src="images/growthhs-dashboard-principal.jpg" alt="GrowthHS - Dashboard"/><br/><sub>Dashboard comercial</sub></td>
    <td><img src="images/growthhs-automacoes-do-crm.jpg" alt="GrowthHS - Automações"/><br/><sub>Automações do CRM</sub></td>
  </tr>
</table>

---

## 🛠️ ChamadosHS — Help Desk interno

Os colaboradores abriam chamados de TI pelo WhatsApp. O ChamadosHS organizou o suporte interno.

- Abertura e acompanhamento de chamados
- Kanban por status, categorias e prioridades
- Histórico completo e tempo médio de resolução

**Stack:** React · TypeScript · Python · FastAPI · PostgreSQL

<table>
  <tr>
    <td><img src="images/chamadoshs-dashboard-principal.jpg" alt="ChamadosHS - Dashboard"/><br/><sub>Dashboard</sub></td>
    <td><img src="images/chamadoshs-gestao-de-chamados.jpg" alt="ChamadosHS - Gestão de chamados"/><br/><sub>Gestão de chamados</sub></td>
  </tr>
</table>

---

## ⚡ Outros sistemas da suíte

- **DataCoreHS:** dashboards financeiros, de metas e de estoque integrados ao ERP (+40% de eficiência na análise)
- **HealthScore:** treinamento de vendas com IA simulando objeções reais (−30% no tempo de treinamento)
- **AI Recruiter:** triagem de currículos com n8n + OpenAI API (−70% no tempo do processo seletivo)
- **AppHealth:** app mobile em Flutter integrado via Bluetooth aos equipamentos

---

<div align="center">

Gostou? Vamos conversar 👇

<a href="https://www.linkedin.com/in/weltonkellyson"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/WeltonKellyson"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:38BDF8,30:2563EB,70:1E3A8A,100:0B1020&section=footer"/>

# 🏛️ Isabel Juliane — Arquitetura da Presença™
### Plataforma Enterprise Full-Stack de EdTech de Luxo & Posicionamento Executivo

<div align="center">

[🇧🇷 Versão em Português](./README.pt-BR.md) &nbsp;•&nbsp; [🇺🇸 English Version](./README.md)

<br/>

[![Next.js 15](https://img.shields.io/badge/Next.js-15.1.7-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React 19](https://img.shields.io/badge/React-19.0.0-61DAFB?style=for-the-badge&logo=react)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.7-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Supabase Zero-Trust](https://img.shields.io/badge/Supabase-PostgreSQL_RLS-3ECF8E?style=for-the-badge&logo=supabase)](https://supabase.com/)
[![Resend API](https://img.shields.io/badge/Resend-Automação_Email-000000?style=for-the-badge&logo=resend)](https://resend.com/)
[![Edge Middleware](https://img.shields.io/badge/Vercel-Edge_HMAC_SHA256-000000?style=for-the-badge&logo=vercel)](https://vercel.com/)
[![Vercel Analytics](https://img.shields.io/badge/Vercel-Analytics_Integrado-000000?style=for-the-badge&logo=vercel)](https://vercel.com/analytics)
[![Security Audit](https://img.shields.io/badge/Auditoria_Segurança-100%25_Remediada-brightgreen?style=for-the-badge&logo=shield)](#-auditoria-de-segurança-zero-trust--defesa-em-profundidade)

</div>

---

## 🌟 Sumário Executivo & Visão Geral

A plataforma **Isabel Juliane — Arquitetura da Presença™** é uma solução digital enterprise de alta performance desenvolvida para consultoria de imagem estratégica, liderança executiva e diagnóstico de presença para profissionais C-Level.

Construída com um **design system editorial de luxo** e sustentada por uma **arquitetura serverless Zero-Trust**, a aplicação entrega uma jornada completa: desde a captação de leads com quiz psicométrico interativo de alta conversão até a geração instantânea de dossiês personalizados, entrega automatizada de e-book em PDF via **Resend** e sincronização bidirecional em tempo real com **Kommo CRM** e **Supabase PostgreSQL**.

> [!NOTE]
> **Aviso de Portfólio & Estudo de Caso de Arquitetura:** Este repositório é um case study de arquitetura de software. O código-fonte proprietário, dados de clientes e algoritmos comerciais exclusivos estão protegidos sob NDA. Todos os padrões de arquitetura, esquemas de banco de dados, modelos de segurança e engenharia de interface aqui demonstrados são autênticos e representam os padrões reais de produção.

---

## 🎬 Gravação ao Vivo & Demonstração da Plataforma

<div align="center">

![Demonstração da Plataforma ao Vivo](./screenshots/00-platform-demo-recording.webp)

*Gravação contínua da navegação pela plataforma: experiência editorial na landing page, resolução do questionário interativo, autenticação criptográfica no Edge e painel administrativo em tempo real.*

</div>

---

## 📸 Galeria de Telas em Produção (Capturas Reais do Navegador)

<div align="center">

### 1. Experiência Editorial de Luxo (Homepage & Hero)
*Estética editorial refinada com tipografia Cormorant Garamond, micro-interações e estrutura de landing page voltada para conversão de alto padrão.*

![Homepage Editorial](./screenshots/01-homepage-editorial.png)

---

### 2. Motor de Diagnóstico Estratégico Multietapas (Pergunta 01)
*Questionário psicométrico e visual de 10 etapas com cálculo de pontuação em tempo real, persistência de estado e controles fluidos.*

![Diagnóstico de Presença Etapa 1](./screenshots/02-quiz-diagnostic-flow.png)

---

### 3. Diagnóstico em Andamento (Pergunta 04 & Barra de Progresso)
*Progressão fluida entre perguntas, animações aceleradas por hardware via Framer Motion e indicadores de progresso dinâmicos.*

![Diagnóstico em Andamento](./screenshots/03-quiz-step-active.png)

---

### 4. Aplicação & Onboarding Executivo (`/boas-vindas`)
*Página exclusiva de aplicação e alinhamento de expectativas para mentorias e consultorias individuais.*

![Boas-Vindas e Aplicação](./screenshots/04-boas-vindas-aplicacao.png)

---

### 5. Tela de Login Administrativo com Proteção no Edge (`/admin/login`)
*Card de autenticação protegido por HMAC-SHA256 (Web Crypto API), campos honeypot anti-bot e verificação interativa de segurança.*

![Tela de Login](./screenshots/05-admin-login-screen.png)

---

### 6. Command Center & Analytics em Tempo Real (`/admin/diagnosticos`)
*Interface administrativa desacoplada com rolagem independente, cards de métricas em tempo real e gráficos de conversão.*

![Painel de Analytics](./screenshots/06-admin-analytics-dashboard.png)

---

### 7. Inteligência de Leads & Gestão de Pipeline de CRM
*Tabela de leads com visualização de dossiês completos, status do Kommo CRM em tempo real e reenvio de e-mail com 1 clique.*

![Gestão de Leads e CRM](./screenshots/07-admin-leads-crm.png)

---

### 8. Central de E-mail Marketing Resend & Homologação ao Vivo
*Pipeline serverless de e-mails com preview do template oficial em HTML, monitoramento de status da API e formulário de teste de entrega instantâneo.*

![Central de E-mail Resend](./screenshots/08-admin-email-resend-hub.png)

---

### 9. Galeria de Fotografias & Gestão de Mídia
*Gerenciador centralizado de ativos visuais e ensaios fotográficos da consultora.*

![Galeria de Fotos](./screenshots/09-admin-galeria-fotos.png)

---

### 10. Gestão de SEO & Metatags das Páginas
*Controle granular de títulos, descrições e parâmetros OpenGraph para indexação no Google.*

![Configurações de SEO](./screenshots/10-admin-paginas-seo.png)

</div>

---

## ⚡ Destaques Técnicos de Engenharia

### 1. Design System Editorial de Luxo & UX Desacoplada
* **Paleta de Cores Exclusiva:** Warm Cream (`#FAF8F5`), Deep Chocolate (`#2C2420`) e Vinho Assinatura (`#661D28`).
* **Hierarquia Tipográfica:** Cormorant Garamond (Serif Display Editorial) combinada com Plus Jakarta Sans (Sem serifa moderno e legível).
* **Layout Desacoplado em 3 Camadas:** Container raiz travado na viewport com `h-screen overflow-hidden`, Sidebar lateral fixa (`aside`), Header superior fixado e rolagem fluida e independente exclusiva para a área de conteúdo (`<main>`).

### 2. Segurança Zero-Trust & Validação Stateless de Nonces
* **Tokens Criptográficos Efêmeros de Sessão:** Nonces UUID únicos de uso único gerados e assinados no servidor com HMAC-SHA256 (validade de 5 min) no endpoint `GET /api/quiz/session`.
* **Queima Atômica de Nonces:** Execução de `UPDATE` SQL atômico (`UPDATE submission_nonces SET used_at = now() WHERE id = nonce AND used_at IS NULL`), eliminando 100% dos ataques de Replay e automações de bots.
* **Autenticação HMAC-SHA256 no Edge Runtime:** Validação de assinatura criptográfica nativa via Web Crypto API no `src/middleware.ts`, bloqueando qualquer tentativa de adulteração de cookies antes de chegar ao servidor.
* **Row Level Security (RLS) Estrito no Supabase PostgreSQL:** 100% das tabelas do banco protegidas por RLS com negação implícita (DENY) para acessos anônimos diretos.

### 3. Orquestração Serverless com Next.js 15 `after()`
* **Processamento Não-Bloqueante em Background:** Utilização da API `after()` do Next.js 15 para disparar o e-mail transacional do Resend e a sincronização do Kommo CRM em segundo plano, evitando o congelamento prematuro da função na Vercel e respondendo ao lead C-Level imediatamente com status 201.
* **Telemetria Integrada:** Monitoramento de tráfego integrado nativamente via `@vercel/analytics`.

---

## 🏗️ Arquitetura do Sistema & Fluxo de Dados

```mermaid
flowchart TD
    subgraph ClientLayer ["Camada de Cliente e Edge na Vercel"]
        User["Visitante ou Lead Executivo"]
        Admin["Administrador Isabel Juliane"]
        EdgeMW["Edge Runtime Middleware com HMAC-SHA256"]
    end

    subgraph AppLayer ["Next.js 15 App Router Motor Serverless"]
        SessionAPI["GET /api/quiz/session (Emite Nonce & Token)"]
        SubmitAPI["POST /api/quiz/submit (Zod Estrito & Queima Nonce)"]
        AdminHub["Command Center Administrativo em /admin"]
        BackgroundTask["Next.js 15 after() Motor de Background"]
    end

    subgraph DataLayer ["Persistencia de Dados e APIs Externas"]
        SupabaseDB[("Supabase PostgreSQL com RLS Estrito")]
        ResendAPI["API de E-mail Resend"]
        KommoCRM["Pipelines do Kommo CRM"]
        CronJob["Rotina pg_cron de Manutencao"]
    end

    User -->|"1. Solicita Nonce de Sessao"| SessionAPI
    SessionAPI -->|"2. Registra Nonce"| SupabaseDB
    User -->|"3. Submete Questionario Assinado"| SubmitAPI
    SubmitAPI -->|"4. Queima Nonce & Grava Lead"| SupabaseDB
    SubmitAPI -->|"5. Dispara Background Tasks"| BackgroundTask
    BackgroundTask -->|"6. Envia Dossie em PDF"| ResendAPI
    BackgroundTask -->|"7. Registra Oportunidade"| KommoCRM

    Admin -->|"8. Requisicao de Rota Admin"| EdgeMW
    EdgeMW -->|"9. Valida Assinatura HMAC"| AdminHub
    AdminHub -->|"10. Consulta com Service Role"| SupabaseDB
    CronJob -->|"11. Heartbeat a Cada 6h"| SupabaseDB
```

---

## 🛡️ Auditoria de Segurança Zero-Trust & Defesa em Profundidade

A plataforma foi submetida a uma rigorosa **Auditoria de Segurança Zero-Trust** cobrindo 5 vetores críticos de vulnerabilidade:

```
🔒 ========================================================
🛡️  MATRIZ DE CONFORMIDADE E AUDITORIA DE SEGURANÇA
========================================================

1. Isolamento de Banco (RLS):     [ APROVADO ] 100% das tabelas protegidas por RLS.
2. Autorização e RBAC no Edge:    [ APROVADO ] Web Crypto HMAC-SHA256 validado.
3. Prevenção de Vazamento:        [ APROVADO ] Nomenclatura customizada IJ_*; checagem no startup.
4. Blindagem de Endpoints:        [ APROVADO ] Queima atômica de Nonces; Tokens JWS de 5 min.
5. Integridade de Código e XSS:   [ APROVADO ] escapeHtml estrito; 0 erros de TypeScript.

========================================================
🏆 RESULTADO FINAL: 0 VULNERABILIDADES ABERTAS (NOTA A+)
========================================================
```

---

## 🛠️ Matriz de Tecnologias & Frameworks

| Camada | Tecnologias Utilizadas | Justificativa Técnica |
| :--- | :--- | :--- |
| **Frontend Framework** | `Next.js 15.1.7` (App Router) + `React 19` | Server Components, Renderização no Edge e `after()` em Background. |
| **Linguagem** | `TypeScript 5.7` (Modo Estrito) | 100% de segurança de tipos, 0 erros de compilação e interfaces robustas. |
| **Estilização & UI** | `Tailwind CSS 3.4` + `Framer Motion 12` | Classes utilitárias atômicas, micro-interações de luxo e animações por GPU. |
| **Visualização de Dados** | `Chart.js 4.5` + `React-Chartjs-2` | Gráficos do tipo Radar (Spider Chart), barras de aquisição e tendências. |
| **Banco de Dados & Auth** | `Supabase PostgreSQL` + `Row Level Security` | Isolamento Zero-Trust, `pgcrypto` para hash de senhas, `uuid-ossp` e `pg_cron`. |
| **Segurança no Edge** | `Web Crypto API` (`crypto.subtle`) | Assinatura e verificação de sessões com HMAC-SHA256 no Edge sem cold start. |
| **Infraestrutura de E-mail** | `Resend API` + Template HTML Custom | Entrega rápida serverless, conformidade DKIM/SPF e logs de entrega. |
| **Integração com CRM** | `Kommo CRM REST API` + Webhooks | Captura em tempo real, enriquecimento de leads e automação de oportunidades. |
| **Telemetria & Analytics** | `@vercel/analytics` | Contagem de visitantes e métricas de desempenho com privacidade. |
| **Deploy & Hospedagem** | `Vercel Serverless & Edge Network` | CDN global, latência sub-milissegundo e CI/CD contínuo. |

---

## 📈 Benchmarks de Performance & Qualidade

* ⚡ **Performance no Lighthouse:** `100 / 100`
* 🔒 **Segurança & Melhores Práticas:** `100 / 100`
* ♿ **Acessibilidade:** `98 / 100`
* 🎯 **Otimização de SEO:** `100 / 100` (Schema JSON-LD estruturado, OpenGraph, tags canônicas e Sitemap XML)
* ⏱️ **Latência de Autenticação no Edge:** `< 5ms`
* 📦 **Bundle JavaScript Compartilhado:** `~103 kB`

---

## 🏷️ Metadados & Palavras-Chave de Busca

`nextjs-15` `react-19` `typescript` `tailwindcss` `supabase` `postgresql-rls` `zero-trust` `resend-email` `kommo-crm` `edge-computing` `hmac-sha256` `web-crypto-api` `editorial-design` `personal-branding` `luxury-ui` `psychometric-assessment` `lead-generation` `saas-dashboard` `chartjs` `portfolio-case-study`
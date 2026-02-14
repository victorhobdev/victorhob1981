# Olá, eu sou o Victor 👋

Sou desenvolvedor com foco em **backend**, **cloud** e **dados** — gosto especialmente de construir sistemas “de vida real”: **APIs**, **autenticação**, **banco relacional**, **agendamentos/jobs**, **integrações** e **observabilidade**.
Concluindo minha formação como estudante de **Sistemas de Informação (UFRRJ)**

- 🎓 **Sistemas de Informação — UFRRJ** (2022–2027)
- 🧠 Certificações: **CS50x (Harvard)** | **Advanced SQL (Kaggle)**
- 🧩 Interesses: **Back-end**, **Cloud (Azure)**, **PostgreSQL/SQL**, **Integrações**, **Automação**

---

## Stack

- **Languages:** Java, Python, SQL, TypeScript, JavaScript, C  
- **Backend:** REST APIs, Auth/JWT, Scheduler/Jobs, Concurrency, Pydantic  
- **Cloud:** Azure Functions, Timer Trigger, App Settings (Env Vars), Logs/Monitoring  
- **Databases:** PostgreSQL (Supabase), MySQL  
- **Frontend:** React, Vite, HTML, CSS  
- **Tools:** Git, GitHub, VS Code, Maven, Apache Tomcat, IntelliJ IDEA, Eclipse  

---

## Projetos em destaque

### 🔹 OpsPulse — Scheduler e Monitor de Rotinas HTTP (Azure Functions + Supabase + React)
Mini SaaS para cadastrar rotinas HTTP e acompanhar execuções com histórico.  
**O que eu pratiquei aqui:** cloud na prática, deploy/config por env vars, autenticação JWT, modelagem relacional, scheduler e confiabilidade.

**Destaques técnicos**
- **API REST** em **Azure Functions (Python)**: CRUD de rotinas, execução manual, histórico (“runs”) e healthcheck  
- **Auth** com **Supabase Auth** e validação de **JWT (Bearer token)** no backend  
- **Scheduler** via **Timer Trigger** com *due window* (`next_run_at <= now`)  
- **Concorrência/lock** (`lock_until/locked_by`) e limite de concorrência para evitar duplicidade (*race conditions*)  
- **PostgreSQL (Supabase)** com **constraints** e **índices** para performance do scheduler e consultas por tempo  
- **Segurança de segredos**: `secret_ref` via env vars; bloqueio de headers sensíveis (Authorization/Cookie/X-API-Key)  
- **Frontend** em **React + TypeScript (Vite)** com auto-refresh para refletir execuções agendadas

> Dica: se você estiver testando rotinas, endpoints como `https://httpbin.org/status/200` e `https://httpbin.org/status/500` são ótimos.

---

### 🔹 ERP para Loja de Artigos Esportivos (Java + SQL)
Sistema ERP em uso contínuo que substituiu planilhas, centralizando **cadastro de produtos**, **controle de estoque** e **registro de vendas** com persistência em banco de dados relacional.

**Destaques técnicos**
- Implementação de **CRUD**, **validações** e **regras de negócio**
- **Modelagem relacional**, consultas **SQL** e integração via **JDBC**
- Evolução contínua com foco em **estabilidade** e **manutenibilidade**
- Versionamento e organização do código com **Git/GitHub**

---

### 🔹 Sincronizador de Catálogo (JavaFX + MySQL + Google Drive API)
Sistema de integração que sincroniza o catálogo público de produtos no Google Drive com o estoque do ERP, usando **metadados (SKU)** como identidade técnica, regras determinísticas e atualizações condicionais por **MD5**.

---

## Contato
- 📩 Email: **victorhob23@gmail.com**
- 🔗 LinkedIn: **linkedin.com/in/victor-ho-barbosa**

# 🧠 Plataforma Educacional SENO

Projeto de desenvolvimento de uma **plataforma educacional online** focada no acesso a conteúdos organizados por série, módulo e assunto. Os alunos poderão assistir a vídeos (YouTube), baixar PDFs, participar de eventos e acompanhar o progresso acadêmico. O sistema terá autenticação, perfis distintos (diretor, professor, aluno, responsáveis, secretário), e será acessível por web, tablet e mobile.

---

## 🗂️ Escopo do Projeto

### 🎯 Objetivo
Desenvolver uma plataforma educacional acessível, organizada e escalável, com foco na experiência do aluno e no controle pedagógico por parte da equipe gestora.

---

## 👨‍🏫 Público-Alvo

- Alunos da Educação Básica
- Professores
- Diretores e Secretários Escolares
- Pais e Responsáveis

---

## ⚙️ Funcionalidades Principais

### ✅ Acesso Público
- Página inicial institucional (missão, visão, contato)
- Política de Privacidade e Termos de Uso
- Agenda de eventos e comunicados

### 🔐 Área Privada
- Autenticação com login/senha e via Google (OAuth)
- Perfis com permissões distintas:
  - **Aluno**: acesso a aulas, materiais, progresso
  - **Professor**: envio de conteúdos, gerência de turmas
  - **Secretário**: cadastro de usuários e conteúdos
  - **Diretor**: painel geral da escola e configurações
  - **Pais/Responsáveis**: visualização de desempenho do aluno

### 🎥 Conteúdo Educacional
- Vídeos incorporados do YouTube
- Upload e download de PDFs
- Organização por Série > Módulo > Assunto

### 📆 Agenda e Eventos
- Lista de eventos escolares
- Visualização mensal/semanal
- Notificações de novos eventos

---

## 🏗️ Arquitetura e Tecnologias

### 🔙 Backend
- **Python + Django REST Framework**
- Autenticação JWT
- Banco de dados PostgreSQL
- Docker e Docker Compose

### 🌐 Frontend
- **React** com Tailwind CSS
- Consumo da API REST
- Design responsivo (desktop, tablet e mobile)

### ☁️ Deploy
- Docker + GitHub Actions (CI/CD)
- Hospedagem: Render, Railway, ou VPS (a definir)

---

## 🧪 Testes
- Testes unitários (Django)
- Testes de integração e e2e (Cypress ou Playwright)
- Pipeline CI/CD com validações

---
## 📁 Estrutura de Pastas


### Descrição

- `backend/`: Contém o backend da aplicação usando Django e Django REST Framework.
- `frontend/`: Frontend em React com Tailwind.
- `infra/`: Configurações de infraestrutura como Docker, nginx, CI/CD.
- `docs/`: Documentos técnicos, backlog, decisões de arquitetura.
- `scripts/`: Scripts de setup, build e manutenção.
- `.env.example`: Template com variáveis de ambiente.


---

## 🗃️ Organização do Código

- **main**: versão estável de produção
- **dev**: integração contínua
- **feature/**: desenvolvimento de funcionalidades
- **hotfix/** e **bugfix/**: correções rápidas

---

## 📌 Status do Projeto

- 🚧 Em desenvolvimento
- ✅ Sprint atual: *Setup Inicial & Docker*
- 📅 Previsão de entrega: **15/12/2025**

---

## 📋 Licença

Este projeto é licenciado sob a [MIT License](LICENSE).

---

## 🤝 Contato

Desenvolvido por [Daniel Castilho Diniz](mailto:danielcastilhodiniz@gmail.com)
GitHub: [github.com/DanielCastilhoDiniz](https://github.com/DanielCastilhoDiniz)




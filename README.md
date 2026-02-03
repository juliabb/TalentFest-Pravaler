# 📌 Sistema RDM (Requisição de Mudança)

![Tela do sistema RDM](./src/assets/tela1.png)

Sistema interno de **Requisição de Mudança (RDM)** desenvolvido para gerenciar solicitações, acompanhamento e fluxo de aprovação de mudanças em sistemas corporativos.

O projeto simula um cenário real de uso interno em empresas, com foco em **organização, rastreabilidade, controle de solicitações e experiência do usuário**.

---

## 🔍 Índice

- [1. Introdução](#1-introdução)
- [2. Sobre o projeto](#2-sobre-o-projeto)
- [3. Funcionalidades](#3-funcionalidades)
- [4. Tecnologias utilizadas](#4-tecnologias-utilizadas)
- [5. Como executar o projeto](#5-como-executar-o-projeto)
- [6. Colaboração](#6-colaboração)
- [7. Considerações finais](#7-considerações-finais)

---

## 1. Introdução

A **Requisição de Mudança (RDM)** é um processo fundamental em ambientes corporativos para garantir que alterações em sistemas sejam realizadas de forma controlada, documentada e aprovada.

Este sistema foi desenvolvido para simular esse fluxo, permitindo o registro, acompanhamento e aprovação de mudanças de forma clara e organizada.

---

## 2. Sobre o projeto

O **Sistema RDM** é uma aplicação web voltada para uso interno, permitindo que usuários criem solicitações de mudança e acompanhem seu status ao longo das etapas de aprovação.

O projeto foi pensado para refletir um **cenário real de empresas de tecnologia**, com separação de responsabilidades, histórico de alterações e controle por perfil de usuário.

> ⚠️ Algumas funcionalidades dependem da API backend, que ainda está em processo de deploy.

---

## 3. Funcionalidades

- 🔐 Autenticação de usuários
- 📝 Criação de requisições de mudança (RDM)
- 📊 Acompanhamento do status das solicitações
- 📄 Visualização de detalhes e histórico
- ✅ Fluxo de aprovação por perfis administrativos
- 🧭 Interface organizada e orientada a etapas

---

## 4. Tecnologias utilizadas

### 🎨 Front-end
- Angular
- TypeScript
- HTML5
- CSS3

### ⚙️ Back-end
- API REST em .NET
- PostgreSQL

---

## 5. Como executar o projeto

### 📋 Pré-requisitos

- Node.js
- Angular CLI

### ▶️ Passos para execução

```bash
# Clone o repositório
git clone https://github.com/juliabb/sistema_RDM.git

# Acesse a pasta do projeto
cd sistema_RDM

# Instale as dependências
npm install

# Execute a aplicação
ng serve

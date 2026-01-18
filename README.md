# 🤖 Bot Gerador Automático de Atas de Reunião

## 📝 Resumo

Projeto corporativo de automação integrado ao Microsoft Teams para geração automática de atas de reunião em PDF, utilizando transcrição de reuniões e fluxos via Power Automate. A solução tem como objetivo garantir padronização, rastreabilidade e redução de esforço manual na documentação de compromissos corporativos.

---

## 🧩 Problema

Após reuniões online, participantes precisam formalizar informações como:

- Título da reunião
- Lista de participantes
- Resumo dos principais pontos discutidos
- Compromissos assumidos e prazos

Esse processo é geralmente manual, propenso a falhas e consome tempo, podendo resultar em inconsistências ou perda de informações.

---

## 🎯 Objetivo da Solução

Automatizar a geração de atas após reuniões no Teams, permitindo que o usuário receba um PDF formatado por e-mail com todas as informações essenciais capturadas da transcrição.

---

## 👥 Contexto de Uso

A solução foi projetada para colaboradores que participam de reuniões internas e precisam documentar decisões e responsabilidades de forma padronizada e rastreável.

---

## 🏗️ Arquitetura do Fluxo

Fluxo simplificado da solução:

```mermaid
flowchart TD
    A[Usuário no Microsoft Teams] --> B[Bot - Copilot Studio]
    B --> C[Transcrição da Reunião]
    C --> D[Power Automate - Processamento]
    D --> E[Geração de PDF]
    E --> F[Envio via E-mail]
````

---

## 🛠️ Tecnologias Utilizadas

* **Microsoft Teams** — Interface com o usuário
* **Microsoft Copilot Studio** — Construção do bot
* **Transcrição de Reuniões** — Fonte de dados textual
* **Power Automate** — Execução do fluxo e formatação
* **E-mail Corporativo** — Entrega do documento final

---

## ⚙️ Funcionamento do Sistema

1. Usuário participa de uma reunião no Teams.
2. Ao finalizar, aciona o bot pelo Teams.
3. O bot obtém a transcrição da reunião.
4. Power Automate processa e extrai informações relevantes.
5. O fluxo gera a ata em PDF padronizado.
6. O documento é enviado por e-mail ao solicitante.

---

## 📈 Resultados e Impacto

* Redução do esforço manual na produção de atas
* Maior padronização e conformidade
* Rastreabilidade de compromissos e decisões
* Menor risco de perda de informações importantes
* Agilidade pós-reunião

---

## 🚧 Status

✔ Implementado internamente
✔ Validado com usuários
✔ Executando via Power Automate
⚠ Código e prints internos não disponibilizados por política corporativa

---

## 📚 Lições Aprendidas

* Integração entre ferramentas Microsoft 365
* Construção de bots com Copilot Studio
* Automação orientada a fluxos corporativos
* Modelagem de processos com transcrição da reunião
* Documentação técnica + requisitos de negócio

---
## 📎 Evidências e Documentação

Este repositório contém:

📁 `/docs`

* Caso de uso em PDF (sem dados sensíveis)
* Diagrama da arquitetura

📁 `/assets`

* Diagramas do fluxo (editar via draw.io)

> Observação: Prints sensíveis do ambiente interno não serão disponibilizados.

---

## 🧑‍💻 Autora

**Vitória Moreira**
*Engenharia de IA Aplicada e Automação*

---

## 📫 Contato

* LinkedIn: *linkedin.com/in/vitória-rodrigues-a0b14b191 *
* E-mail: *vitoriarodrigs1502@gmail.com*

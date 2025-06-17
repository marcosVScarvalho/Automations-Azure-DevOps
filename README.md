# Projeto: Automação Azure DevOps

## 1 - Objetivo

### Desafio Inicial
- Criar um repositório chamado: `automations-azure-devops`
- Publicar um arquivo `README.md` com a descrição do projeto, objetivos e instruções iniciais.

### Desafio Principal
Automatizar tarefas dentro do Azure DevOps com os seguintes objetivos:

- Listar todos os projetos do Azure DevOps
- Gerar arquivos: `projetos.csv`, `projetos.json`
- Listar repositórios por projeto
- Gerar arquivos: `repos.csv`, `repos.json`
- Listar todos os usuários com nível de acesso **Stakeholder** e **Basic**
- Gerar arquivos: `users.csv`, `users.json`

### Desafio Extra
- Gerar um relatório com gráficos interativos ou estáticos

---

## 2 - Fontes Principais Utilizadas

- **PoC (Proof of Concept)**
- **Opengrep:**
  - Repositório principal: [https://github.com/opengrep/opengrep](https://github.com/opengrep/opengrep)
  - Regras e templates: [https://github.com/opengrep/opengrep-rules](https://github.com/opengrep/opengrep-rules)
- **Azure DevOps do BBTS Lab:**
  - [https://dev.azure.com/bbts-lab/](https://dev.azure.com/bbts-lab/)
  - [https://dev.azure.com/bbts-lab/_git/gesec-disen-devsecops-automations](https://dev.azure.com/bbts-lab/_git/gesec-disen-devsecops-automations)

---

## 3 - Fontes de Estudo

- Documentação Oficial
- Azure DevOps REST API Reference
- Documentação Azure DevOps CLI
- Cursos e Tutoriais:
  - Microsoft Learn: [https://learn.microsoft.com/en-us/training/](https://learn.microsoft.com/en-us/training/)
  - YouTube (Cloud Advocate, TechWorld with Nana, Microsoft DevOps)
- Ferramentas e Bibliotecas Úteis:
  - `az devops` (Azure CLI)
  - PowerShell com módulos AzureDevOps
  - Python com bibliotecas `requests`, `pandas`, `matplotlib`, `plotly`

---

## 4 - Comandos Git que serão Utilizados no projeto + Definições:

 - O que é o Git:
  - Git se Baseia em um controle de versão (Historico do Projeto), com ele é possivel criarmos repositorios para nossa linha do tempo tambem chamada de Branch, commits são pontos na nossa branch, stage area local de organização do projeto para enviar o commit

- `git -v` — Verifica a versão instalada do Git  
- `git init` — Inicializa o repositório local  
- `git add .` — Adiciona todos os arquivos para staging  
- `git commit -m "mensagem"` — Realiza um commit com mensagem  

# 🧠 Guia Essencial de Git e GitHub

Este repositório tem como objetivo apresentar os conceitos fundamentais de **Git** e **GitHub**, ideal para iniciantes que desejam entender como versionar e colaborar em projetos de software.

---

## 📌 O que é Git?

Git é um sistema de controle de versão distribuído, criado por Linus Torvalds, que permite acompanhar mudanças no código-fonte ao longo do tempo. É amplamente utilizado em projetos de software para garantir organização, rastreabilidade e colaboração.

---

## 🌐 O que é GitHub?

GitHub é uma plataforma online que hospeda repositórios Git. Ela facilita a colaboração entre desenvolvedores, oferecendo ferramentas como pull requests, issues, e integração contínua.

---

## 🛠️ Conceitos Fundamentais

### ✅ Repositório
Local onde os arquivos e histórico de versões do projeto são armazenados.

### ✅ Commit
Registro de uma alteração no projeto. Deve conter uma mensagem clara explicando o que foi modificado.

### ✅ Branch
Ramificação do projeto usada para desenvolver funcionalidades ou correções sem afetar o código principal.

### ✅ Merge
Ato de unir alterações de uma branch ao projeto principal.

### ✅ Pull Request (PR)
Solicitação para mesclar alterações de uma branch (geralmente de um fork) ao repositório original.

### ✅ Fork
Cópia de um repositório para sua conta GitHub, permitindo modificar sem afetar o original.

### ✅ Clone
Cópia local de um repositório remoto para trabalhar offline.

### ✅ Issue
Ferramenta para reportar bugs, sugerir melhorias ou discutir ideias.

### ✅ .gitignore
Arquivo que define quais arquivos ou pastas devem ser ignorados pelo Git.

---

## 🚀 Fluxo Básico de Uso

1. Instale o Git em sua máquina.
2. Configure seu nome e e-mail:
   ```bash
   git config --global user.name "Seu Nome"
   git config --global user.email "seu@email.com"
3. Crie um repositório local:
   ```bash
   git init
4. Ou clone um repositório:
   ```bash
   git clone <url-do-repositorio>
5. Faça as alterações e resgistre com commits:
   ```bash
   git add .
   git commit -m "Descrição da mudança"
6. Envie para o GitHub:
   ```bash
   git push -u origin <nome-da-branch>

## 📚 Comandos úteis 
```bash
git init                    # Inicializa um repositório Git
git status                  # Mostra o estado atual do repositório
git add <arquivo>           # Adiciona arquivo ao commit
git commit -m "mensagem"    # Cria um commit
git log                     # Exibe histórico de commits
git branch                  # Lista branches
git checkout -b nova-branch # Cria e muda para nova branch
git merge <branch>          # Mescla branch ao atual
git pull                    # Atualiza repositório local com remoto
git push                    # Envia alterações para o remoto

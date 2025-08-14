# 📌 Comandos Git Essenciais — Add, Branch e Delete

Este guia contém os comandos mais usados para trabalhar com **branches** no Git e gerenciar alterações no repositório.

---

## 🔹 1. Adicionar Arquivos ao Git

Adicionar alterações para serem commitadas:

```bash
# Adicionar um arquivo específico
git add nome_do_arquivo.ext

# Adicionar todos os arquivos modificados
git add .
💡 O git add . adiciona todos os arquivos modificados no diretório atual.

🔹 2. Criar e Alternar Branches
Criar uma nova branch e mudar para ela:

bash
Copiar
Editar
# Criar uma branch
git branch nome-da-branch

# Criar e já entrar nela
git checkout -b nome-da-branch
Alternar entre branches existentes:

bash
Copiar
Editar
git checkout nome-da-branch
Ver todas as branches:

bash
Copiar
Editar
git branch
🔹 3. Deletar Branch
Deletar uma branch local:

bash
Copiar
Editar
# Deletar branch local
git branch -d nome-da-branch

# Forçar exclusão (caso não esteja mergeada)
git branch -D nome-da-branch
Deletar uma branch remota:

bash
Copiar
Editar
git push origin --delete nome-da-branch
🔹 4. Fluxo Comum de Trabalho
bash
Copiar
Editar
# 1. Criar e mudar para nova branch
git checkout -b feature/nova-funcionalidade

# 2. Adicionar arquivos
git add .

# 3. Commitar alterações
git commit -m "Implementa nova funcionalidade"

# 4. Enviar branch para o repositório remoto
git push origin feature/nova-funcionalidade
🔹 5. Tabela Resumo
Ação	Comando
Adicionar arquivo específico	git add nome_do_arquivo.ext
Adicionar todos os arquivos	git add .
Criar branch	git branch nome-da-branch
Criar e trocar para nova branch	git checkout -b nome-da-branch
Trocar de branch	git checkout nome-da-branch
Listar branches	git branch
Deletar branch local	git branch -d nome-da-branch
Forçar exclusão de branch local	git branch -D nome-da-branch
Deletar branch remota	git push origin --delete nome-da-branch

✍️ Autor: Seu Nome
📅 Atualizado em: Agosto/2025

nginx
Copiar
Editar

Se quiser, já posso te gerar também um **README.md com formatação de cores e ícones** para ficar
```

# Comandos Git Essenciais - Add, Branch e Delete

Este guia contém os comandos mais usados para trabalhar com branches no Git e gerenciar alterações no repositório.

---

## 1. Adicionar Arquivos ao Git

Adicionar alterações para serem commitadas:

- Adicionar um arquivo específico

```bash
git add nome_do_arquivo.ext
```

- Adicionar todos os arquivos modificados

```bash
git add .
```

O comando `git add` . adiciona todos os arquivos modificados no diretório atual.

---

## 2. Criar e Alternar Branches

Criar uma nova branch e mudar para ela:

- Criar uma branch

```bash
git branch nome-da-branch
```

- Criar e já entrar nela

```bash
git checkout -b nome-da-branch
```

- Alternar entre branches existentes:

```bash
git checkout nome-da-branch
```

- Ver todas as branches:

```bash
git branch -a
```

---

## 3. Deletar Branch

- Deletar uma branch local

```bash
git branch -d nome-da-branch
```

- Forçar exclusão (caso não esteja mergeada)

```bash
git branch -D nome-da-branch
```

- Deletar uma branch remota:

```bash
git push origin --delete nome-da-branch
```

---

## 4. Fluxo Comum de Trabalho

1. Criar e mudar para nova branch

```bash
git checkout -b feature/nova-funcionalidade
```

2. Adicionar arquivos

```bash
git add .
```

3. Commitar alterações

```bash
git commit -m "Implementa nova funcionalidade"
```

4. Enviar branch para o repositório remoto

```bash
git push origin feature/nova-funcionalidade
```

---

## 5. Tabela Resumo

| Ação                            | Comando                                 |
| ------------------------------- | --------------------------------------- |
| Adicionar arquivo específico    | git add nome_do_arquivo.ext             |
| Adicionar todos os arquivos     | git add .                               |
| Criar branch                    | git branch nome-da-branch               |
| Criar e trocar para nova branch | git checkout -b nome-da-branch          |
| Trocar de branch                | git checkout nome-da-branch             |
| Listar branches                 | git branch                              |
| Deletar branch local            | git branch -d nome-da-branch            |
| Forçar exclusão de branch local | git branch -D nome-da-branch            |
| Deletar branch remota           | git push origin --delete nome-da-branch |

---

Autor: Paulo Adson
Atualizado em: 13/08/2025

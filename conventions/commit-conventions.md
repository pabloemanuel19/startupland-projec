# Convenções de Commit

Este documento define o padrão para mensagens de commit neste repositório, garantindo clareza e consistência no histórico.

---

## Estrutura da mensagem:

```bash
<tipo>(escopo opcional): <descrição curta>

[descrição detalhada opcional]

[footer opcional]
```

---

## Tipos de commit:

| Tipo     | Descrição                                                          |
| -------- | ------------------------------------------------------------------ |
| feat     | Nova funcionalidade.                                               |
| fix      | Correção de bug.                                                   |
| docs     | Alterações na documentação (README, etc.).                         |
| style    | Ajustes que não afetam a lógica (espaços, ponto e vírgula, etc.).  |
| refactor | Alterações no código que não corrigem bugs nem adicionam recursos. |
| perf     | Melhorias de desempenho.                                           |
| test     | Adição ou modificação de testes.                                   |
| build    | Alterações em build, dependências ou ferramentas.                  |
| ci       | Alterações em scripts de integração contínua.                      |
| chore    | Tarefas diversas que não afetam o código de produção.              |
| revert   | Reversão de commit anterior.                                       |
| cleanup  | Limpeza de código (comentários por exemplo.).                      |

---

## Exemplos:

- `git commit -m "veja os exemplos de mensagens abaixo"`
  - `feat(auth): adicionar login com Google`
  - `fix(api): corrigir erro 500 ao criar usuário`
  - `docs: atualizar instruções de instalação`
  - `style: ajustar identação em index.js`
  - `refactor(core): simplificar lógica de autenticação`
  - `perf: melhorar tempo de carregamento inicial`
  - `test(auth): adicionar teste para fluxo de recuperação de senha`

---

## Boas práticas:

- Descrição curta com até 72 caracteres.
- Usar imperativo: "adicionar" em vez de "adicionando" ou "adicionado".
- Sempre revisar a mensagem antes de commitar.
- Commits pequenos e focados em uma única mudança.

---

Autor: Paulo Adson
Atualizado em: 13/08/2025

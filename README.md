# Guia de Trabalho – Engenharia de Software

## 📘 Visão Geral
Este repositório será utilizado para organizar todo o fluxo de documentação, requisitos, tarefas e entregas da disciplina de **Engenharia de Software – UNIFEOB 2026.1**.

Os alunos irão trabalhar de forma profissional, usando **GitHub** como ferramenta de versionamento, rastreabilidade, documentação e colaboração.

Este documento explica **exatamente** como funciona o fluxo completo: 
Requisito → Issue → Branch → PR → Merge → Atualização do Documento.

---

# 🧭 1. Estrutura do Repositório
```
/docs
   requisitos.md
   casos-de-uso.md
/design
   uml/
.github/
   ISSUE_TEMPLATE/
   PULL_REQUEST_TEMPLATE.md
README.md
```

---

# 📝 2. Onde escrever os requisitos
Os requisitos do projeto são escritos **no arquivo oficial:**
```
/docs/requisitos.md
```

Sempre que forem criados ou revisados, o processo deve ser:
1. Criar uma *Issue* para o requisito.
2. Criar uma *branch* para editar o arquivo.
3. Atualizar o arquivo `requisitos.md`.
4. Abrir um *Pull Request* (PR).
5. O PR fechará automaticamente a Issue usando `Closes #numero`.

---

# 🏷️ 3. Issues – Como criar
Cada requisito (RF, RNF, RN) deve ser registrado como uma Issue.

Dentro de uma Issue devem ter:
- Descrição clara
- Critérios de aceitação ou verificação
- Labels (RF, RNF, etc.)
- Milestone (Requisitos)

Exemplo:
```
Título: RF01 — Login do usuário
Descrição: O sistema deve permitir que o usuário faça login com e-mail e senha.
Critérios:
- Validar credenciais
- Retornar erro quando inválido
- Registrar tentativas
```

---

# 🏷️ 4. Labels – Para que servem
Labels ajudam a organizar e filtrar as Issues.

As principais labels são:
- `RF` – Requisito Funcional
- `RNF` – Requisito Não Funcional
- `Regra-de-Negócio`
- `Prioridade-Alta`
- `Backend`
- `Documentação`
- `Dúvida`

Cada Issue deve ter pelo menos **uma** dessas labels.

---

# 🎯 5. Milestones – Como usar
Milestones agrupam Issues relacionadas a uma **entrega**.

Nesta fase estamos usando:
```
Milestone: Requisitos
```

Quando todas as Issues desse milestone forem concluídas, significa que aquela etapa do projeto foi **entregue**.

---

# 🌿 6. Branches – Como criar e nomear
Quando for editar algo, **nunca** trabalhar direto na main.

Padrão de nome de branch:
```
doc/requisitos-aula03
fix/rf01-login
feature/rf03-cadastro
```

---

# 🔀 7. Pull Requests (PR) – Como abrir
Depois de editar o arquivo `requisitos.md`, criar um PR.

O PR deve conter:
```
# Descrição
Explicar o que foi alterado.

# Issues Relacionadas
Closes #XX (se resolver totalmente a issue)
Relates to #YY (se apenas relaciona)

# Checklist
- [ ] Atualizei requisitos.md
- [ ] A Issue tem labels
- [ ] A Issue está no milestone Requisitos
```

O professor ou outro grupo fará a **revisão** do PR.

---

# ✔ 8. Fluxo completo (resumo profissional)

```
1) Criar Issue
2) Criar branch
3) Editar requisitos.md
4) Commit + Push
5) Abrir PR
6) Revisão (peer review)
7) Merge na main
8) Issue fechada automaticamente
```

É exatamente assim que equipes de desenvolvimento trabalham em empresas.

---

# 🚀 9. Entregas obrigatórias da Aula 03
- `docs/requisitos.md` com pelo menos:
  - 4 RF
  - 2 RNF
  - 2 Regras de Negócio
- Issues criadas com labels e milestone
- 1 Pull Request abrindo alterações

---

# 📚 10. Próximos passos
A **Aula 04** trabalhará Casos de Uso (textuais) e depois diagramas.

Continue organizando tudo dentro do GitHub.

---

Professor: **Max Streicher Vallim** – Engenharia de Software – UNIFEOB 2026.1
Exibindo README.md…

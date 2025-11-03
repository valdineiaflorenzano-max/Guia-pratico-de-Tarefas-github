# Guia-pratico-de-Tarefas-github


gerenciador-de-tarefas/
    README.md
    CONTRIBUTING.md
    CODE_OF_CONDUCT.md
    LICENSE
    .gitignore
    package.json
    .github/
        workflows/
            ci.yml
    src/
        index.html
        css/
            style.css
        js/
            main.js
        assets/
            logo.png

           ---
name: 🐛 Reportar bug
about: Algo não está funcionando como deveria
title: "[BUG] Descrição breve"
labels: bug
assignees: ''
---

### Descrição
Explique o problema encontrado.

### Passos para reproduzir
1. Vá para '...'
2. Clique em '...'
3. Veja o erro

### Comportamento esperado
Descreva o que deveria acontecer.

### Capturas de tela (opcional)
Se aplicável, adicione imagens.

### Ambiente
- Navegador: [ex: Chrome 120]
- Sistema operacional: [ex: Windows 10]

---
name: ✨ Solicitar funcionalidade
about: Sugira uma ideia para melhorar o projeto
title: "[FEATURE] Descrição breve"
labels: enhancement
assignees: ''
---

### Descrição
Explique a nova funcionalidade ou melhoria.

### Motivo
Por que isso é útil para o projeto?

### Possível solução
Descreva como poderia ser implementado.

### Considerações adicionais
Qualquer outro detalhe relevante.

## 📝 Descrição
Explique brevemente o que foi alterado ou adicionado.

## ✅ Tipo de mudança
Marque o que se aplica:
- [ ] Novo recurso (feature)
- [ ] Correção de bug (fix)
- [ ] Atualização de documentação (docs)
- [ ] Alteração de estilo ou layout (style)
- [ ] Refatoração (refactor)
- [ ] Tarefa administrativa (chore)

## 📸 Evidências
Se possível, adicione prints ou GIFs.

## 🔗 Issue relacionada
Closes # (número da issue)

## 📦 Checklist
- [ ] Código testado localmente
- [ ] Commits semânticos e claros
- [ ] PR vinculado a uma issue/milestone

🗓 Milestones e Issues — na prática

Crie no GitHub (web) em Issues → Milestones:

🧭 Exemplo de milestones
Nome	Descrição	Prazo
v0.1.0 - Estrutura Base	Repositório inicial e primeira versão funcional	2025-11-10
v0.2.0 - Funcionalidades Extras	Melhorias visuais e novas features	2025-12-01

Depois, vincule Issues e Pull Requests a cada milestone.
Exemplo:

Issue #1: Criar formulário de tarefas (feature_request.md)

Issue #2: Corrigir botão de exclusão (bug_report.md)

Pull Request #3: feat: adiciona formulário de tarefas — Closes #1

🧩 Exemplo de histórico de Pull


🧩 Exemplo de histórico de Pull Requests documentados
Data	Tipo	Título	Issue vinculada	Milestone
2025-11-02	chore	inicializa repositório com estrutura base	—	v0.1.0
2025-11-02	docs	adiciona README, LICENSE e CONTRIBUTING	—	v0.1.0
2025-11-02	feat	cria página inicial com lista de tarefas	#1	v0.1.0
2025-11-02	feat	implementa salvamento no localStorage	#2	v0.1.0
2025-11-02	style	melhora visual e espaçamento do layout	—	v0.1.0
2025-11-02	fix	corrige botão de exclusão de tarefa	#3	v0.1.0

# 🤝 Como Contribuir

Obrigado por querer contribuir com o **LIFE OS: Pixel Realms**! ⚔️

## 🐛 Reportar um Bug

1. Vá em **[Issues](../../issues)** → **New Issue**
2. Use o título: `[BUG] Descrição curta do problema`
3. Inclua:
   - O que aconteceu
   - O que era esperado
   - Navegador e sistema operacional
   - Passos para reproduzir

## 💡 Sugerir uma Funcionalidade

1. Abra uma **Issue** com o título: `[FEAT] Nome da funcionalidade`
2. Descreva o que você quer e por que seria útil

## 🔧 Enviar um Pull Request

1. Faça um **fork** do repositório
2. Crie uma branch descritiva:
   ```bash
   git checkout -b feat/nome-da-feature
   # ou
   git checkout -b fix/nome-do-bug
   ```
3. Faça suas alterações no `index.html`
4. Commit com mensagem clara (padrão Conventional Commits):
   ```bash
   git commit -m "feat: adiciona sistema de conquistas"
   git commit -m "fix: corrige contagem de streak"
   git commit -m "docs: atualiza README"
   ```
5. Envie o PR e descreva o que foi alterado

## 📐 Padrões do Projeto

- **Zero dependências externas** — tudo em HTML/CSS/JS puro
- **Arquivo único** — toda a app vive em `index.html`
- **localStorage** para persistência — sem backend
- Comentários em **português** no código
- Acessibilidade: use `aria-label` em elementos interativos

## 🌟 Ideias de Contribuição

- [ ] PWA (installable, offline)
- [ ] Exportar/importar progresso em JSON
- [ ] Mais avatares e temas visuais
- [ ] Missões recorrentes (semanal/mensal)
- [ ] Sons adicionais (8-bit music)
- [ ] Modo multiplayer real (Firebase/Supabase)
- [ ] Missões com sub-tarefas (checklist)
- [ ] Estatísticas semanais/mensais

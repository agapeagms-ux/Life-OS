# 📋 Changelog

Todas as mudanças relevantes deste projeto serão documentadas aqui.

Formato baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/),
versionamento segue [Semantic Versioning](https://semver.org/lang/pt-BR/).

---

## [3.0.0] - 2026-10-26

### ✨ Adicionado
- Tema Claro/Escuro com toggle no header
- Barra de XP real com sistema de level-up animado
- Modal de Level Up com confetti e som 8-bit exclusivo
- Criador de missões personalizadas (título, descrição, categoria, ouro)
- Botão de deletar missões customizadas
- Sistema de Streaks (dias consecutivos de uso)
- Timer de contagem regressiva até o próximo reset diário
- Dungeon Súbita limitada a 1 uso por dia com cooldown visual
- Log de atividades com timestamp e histórico de até 20 entradas
- Barra de progresso coletiva da Guilda
- 3 novos avatares (Elfa Disciplinada, Zumbi Produtivo, Dragão do Caos)
- Atributos vitais sobem +10% por missão (era +15%)
- Aria-labels e roles semânticos para acessibilidade
- Banner de reset diário ao detectar novo dia
- README, LICENSE, .gitignore, CONTRIBUTING e SECURITY

### 🔧 Melhorado
- Botões com estado `disabled` correto (sem cursor pointer quando inativo)
- Shop: botão desabilitado automaticamente se ouro insuficiente
- Quests concluídas com opacidade e filtro grayscale
- Scroll customizado no log de atividades
- Layout responsivo aprimorado (2 colunas em tablets)
- Sons retrô melhorados com novo tipo `levelup` e `buy`

### 🐛 Corrigido
- `selectAvatar` usando `event` global em vez de parâmetro (corrigido)
- Missões custom não sendo deletadas do array correto

---

## [2.4.0] - Versão Original

### ✨ Adicionado
- Layout RPG em 3 colunas com grid CSS
- Sistema básico de ouro e nível
- 4 missões diárias fixas
- 4 atributos vitais com barras de progresso
- Dungeon Súbita com eventos aleatórios
- Loja de recompensas reais
- Vila multiplayer simulada com avatares de amigos
- Web Audio API para sons retrô 8-bit (success, coin)
- Animação flutuante de ganho de ouro
- Persistência via localStorage
- Seletor de avatar com 6 opções
- Toggle de áudio

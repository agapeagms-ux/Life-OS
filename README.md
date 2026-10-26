# 🛡️ LIFE OS: Pixel Realms v3.0

> **Sistema Operacional da Vida Real** — Um RPG de produtividade gamificado para transformar seus hábitos diários em missões épicas.

![Preview](https://img.shields.io/badge/versão-3.0-8b5cf6?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML-puro-06b6d4?style=for-the-badge&logo=html5)
![Zero dependências](https://img.shields.io/badge/dependências-zero-10b981?style=for-the-badge)

---

## ✨ O Que é?

**LIFE OS: Pixel Realms** é uma aplicação web 100% estática (sem backend, sem framework) que transforma sua vida real em um jogo RPG. Cada hábito saudável vira uma missão, cada conquista gera recompensas reais que você define.

---

## 🆕 Novidades da v3.0

| Recurso | Descrição |
|---|---|
| 🌓 **Tema Claro/Escuro** | Alterne entre dark e light com um clique |
| 📊 **Barra de XP real** | Sistema de XP por missão com level-up animado |
| 🎉 **Confetti no Level Up** | Celebração visual ao subir de nível |
| 🔔 **Modal de Level Up** | Popup animado com som retrô 8-bit |
| ➕ **Criador de Missões** | Crie missões totalmente personalizadas |
| 🗑️ **Delete Missão** | Remova missões custom quando quiser |
| 🔥 **Sistema de Streaks** | Conta dias consecutivos de uso |
| ⏱️ **Timer de Reset** | Contagem regressiva até a meia-noite |
| ♿ **Acessibilidade** | `aria-label`, roles semânticos, `role="dialog"` |
| 📜 **Log de Atividades** | Histórico das últimas 20 ações com timestamp |
| 📈 **Progresso da Guilda** | Barra coletiva de missões e ouro |
| 🦊 **+3 Avatares** | 9 avatares disponíveis (eram 6) |
| 🎲 **Dungeon por dia** | Dungeon Súbita limitada a 1x/dia |

---

## 🚀 Como Usar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/SEU_USUARIO/life-os-pixel-realms.git
   cd life-os-pixel-realms
   ```

2. **Abra direto no navegador:**
   ```bash
   # Basta abrir o arquivo index.html no seu navegador favorito
   open index.html        # macOS
   start index.html       # Windows
   xdg-open index.html    # Linux
   ```

3. **Ou use um servidor local simples:**
   ```bash
   # Com Python 3
   python -m http.server 8080
   # Acesse: http://localhost:8080
   ```

> Nenhuma instalação, nenhuma dependência, nenhum backend necessário!

---

## 🎮 Mecânicas do Jogo

### Atributos Vitais
- 🔋 **Vitalidade** — Hábitos físicos (agua, exercício, sono)
- 🪙 **Finanças** — Controle financeiro e poupança
- 🧠 **Sabedoria** — Leitura, aprendizado, meditação
- 🤝 **Social** — Conexões humanas e empatia

### Sistema de Progressão
```
Missão → XP + Ouro → Level Up → Modal de Celebração 🎉
```
- Cada nível requer `nível × 100` XP
- Stats sobem até 100% ao completar missões

### Dungeon Súbita
- Evento aleatório 1x por dia
- Desafio rápido (ex: "Faça 15 flexões!") com recompensa extra

### Loja de Recompensas
- Converta ouro ganho em recompensas **reais** que você define
- Sem culpa: você mereceu! 🎁

---

## 🏗️ Estrutura

```
life-os-pixel-realms/
├── index.html    # Toda a aplicação (HTML + CSS + JS em um único arquivo)
└── README.md     # Este arquivo
```

---

## 💾 Dados Locais

Todos os dados são salvos no `localStorage` do seu navegador com a chave `pixel_realms_v3`. Nenhum dado é enviado para servidores.

---

## 🤝 Contribuindo

Pull requests são bem-vindos! Algumas ideias de melhoria:

- [ ] Múltiplos perfis de jogador
- [ ] Exportar/importar progresso (JSON)
- [ ] Missões recorrentes personalizáveis (semanal/mensal)
- [ ] PWA (installable offline)
- [ ] Multiplayer real com Firebase/Supabase

---

## 📄 Licença

MIT License — use, modifique e compartilhe livremente.

---

<p align="center">
  Feito com ⚔️ e muita cafeína &nbsp;|&nbsp; <em>Transforme hábitos em lendas</em>
</p>

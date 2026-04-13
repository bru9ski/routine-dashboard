# 🏠 Rotina UFPE — Bruno

Dashboard interativo de rotina semanal, checklist, pomodoro e treinos PPL.

## ⚡ Uso Local (sem internet, sem instalação)

1. Faça o download do arquivo `index.html`
2. Dê **duplo clique** para abrir no navegador
3. Pronto — tudo funciona offline

> O app salva seus dados no `localStorage` do navegador. Não apague o histórico do navegador para manter o progresso.

## 📁 Estrutura

```
routine-dashboard/
└── index.html   ← único arquivo, abre direto
```

## 🛠️ Stack

- HTML5 + CSS3 + JavaScript puro
- Zero dependências
- Zero build
- Compativel com Chrome, Firefox, Edge, Safari

## 💾 Dados salvos localmente

| Chave localStorage | Conteúdo |
|---|---|
| `routineState` | Checklist diário por dia |
| `gymLogs` | Registro de treinos (kg, reps, séries) |
| `pomoCount` | Contador de pomodoros |
| `pomoMin` | Minutos totais de foco |

## 📅 Rotina

Split PPL 6x/semana: Push A/B · Pull A/B · Legs A/B · Domingo descanso.

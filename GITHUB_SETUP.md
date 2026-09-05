# 🚀 SETUP GITHUB - COMEÇAR AGORA

Guia passo-a-passo para criar e usar seu repositório 90D no GitHub.

---

## 1️⃣ CRIAR REPOSITÓRIO

### Opção A: Pelo GitHub.com (mais fácil)

1. Vá para [github.com/new](https://github.com/new)
2. Nome do repositório: `90-dias-mudanca-vida` (ou seu preferido)
3. Descrição: "Protocolo de 90 dias para transformação pessoal - 5 pilares"
4. **Público** (para inspirar outros) ou Privado (mais pessoal)
5. ✅ "Add a README file"
6. ✅ "Add .gitignore" → Node (ou None se não usar)
7. Clique: **Create repository**

### Opção B: Por terminal (se preferir)

```bash
# Criar pasta local
mkdir 90-dias-mudanca-vida
cd 90-dias-mudanca-vida

# Inicializar git
git init
git add .
git commit -m "Initial commit - 90D Protocol"

# No GitHub: cria repo vazio (sem README)
# Depois conecta:
git remote add origin https://github.com/SEU-USER/90-dias-mudanca-vida.git
git branch -M main
git push -u origin main
```

---

## 2️⃣ ESTRUTURA DE PASTAS

Crie esta estrutura no seu repositório:

```
90-dias-mudanca-vida/
│
├── README.md                    ← Visão geral do protocolo
├── PROTOCOLO.md                 ← Guia detalhado com metas
├── TEMPLATES.md                 ← Templates copiar/colar
├── GITHUB_SETUP.md              ← Este arquivo
│
├── metas/
│   ├── Ciclo_1_Metas.md        ← Metas do ciclo 1 (customizadas)
│   ├── Ciclo_2_Metas.md        ← Metas do ciclo 2 (customizadas)
│   └── Ciclo_3_Metas.md        ← Metas do ciclo 3 (customizadas)
│
├── days/                        ← Um arquivo por dia
│   ├── Day_01.md
│   ├── Day_02.md
│   └── ... (até Day_90.md)
│
├── reviews/                     ← Análises e reflexões
│   ├── Week_1_Review.md
│   ├── Week_2_Review.md
│   └── ...
│   ├── Month_1_Review.md
│   ├── Month_2_Review.md
│   ├── Month_3_Review.md
│   └── FINAL_90D_REVIEW.md
│
├── statistics/                  ← Dados para gráficos
│   ├── stats.json              ← Dados brutos
│   ├── burndown.md             ← Progresso visual
│   └── heatmap.md              ← Atividade diária
│
├── docs/                        ← Documentação extra (opcional)
│   └── Mindset.md              ← Mantras, motivação
│
└── .gitignore                   ← Ignorar arquivos temporários
```

---

## 3️⃣ CRIAR ESTRUTURA NO GITHUB

### Via GitHub Web (Simples)

1. Vá ao seu repositório
2. Clique **Add file** → **Create new file**
3. Digite o caminho: `metas/Ciclo_1_Metas.md`
4. Conteúdo: copie de PROTOCOLO.md
5. **Commit** direto

**Repita para todas as pastas e arquivos**

### Via Terminal (Mais rápido)

```bash
# Clonar repo local
git clone https://github.com/SEU-USER/90-dias-mudanca-vida.git
cd 90-dias-mudanca-vida

# Criar pastas
mkdir -p days reviews statistics metas docs

# Criar arquivos iniciais
touch metas/Ciclo_1_Metas.md
touch metas/Ciclo_2_Metas.md
touch metas/Ciclo_3_Metas.md
touch statistics/stats.json
touch statistics/burndown.md

# Criar primeiros dias
for i in {01..90}; do touch days/Day_$i.md; done

# Enviar para GitHub
git add .
git commit -m "Initial setup: 90D Protocol structure"
git push
```

---

## 4️⃣ PREENCHIMENTO INICIAL (Hoje - Dia 0)

Antes de começar Dia 1, customize:

### A. Customize `/metas/Ciclo_1_Metas.md`

Copie de PROTOCOLO.md mas **personalize:**

```markdown
# METAS CICLO 1 - CUSTOMIZADAS

## 💪 SAÚDE
- Exercício 4x/semana: [tipo específico: corrida/yoga/academia]
- Dormir 8h: [hora fixa: 23:00 até 07:00]
- Nutrição: [sua estratégia: meal prep/app/manual]

## 💰 FINANÇAS
- Economia: [meta real: R$ X por mês]
- Renda extra: [seu plano: freelance/side project/venda]
- Redução: [onde cortar: assinaturas/alimentação/diversão]

[... customizar outros pilares]
```

### B. Customize `/statistics/stats.json`

Template para rastrear dados:

```json
{
  "start_date": "2026-09-05",
  "days_completed": 0,
  "total_points": 0,
  "best_day": {"day": 0, "points": 0},
  "best_week": {"week": 0, "points": 0},
  "current_streak": 0,
  "longest_streak": 0,
  "pillar_progress": {
    "saude": 0,
    "financas": 0,
    "espiritualidade": 0,
    "relacionamentos": 0,
    "desenvolvimento": 0
  },
  "level": "Egg",
  "weekly_totals": [],
  "monthly_totals": []
}
```

### C. Prepare `days/Day_01.md`

Copie template de TEMPLATES.md e customize

---

## 5️⃣ ROTINA DIÁRIA (15 min máximo)

### Toda Noite (preferencialmente 20-22h)

```bash
# 1. Abra `/days/Day_XX.md` (onde XX = dia atual)
# 2. Preencha checklist (✅ ou ❌)
# 3. Calcule pontos
# 4. Reflita 3 min

# 5. Commit automático:
git add days/Day_XX.md
git commit -m "Day XX: [pontos]/120 - [emoji] [nota rápida]"
git push
```

### Exemplos de commits:
```
Day 01: 105/120 - 🔥 Dia perfeito!
Day 02: 85/120 - ⚠️ Dormi pouco, mas consegui
Day 03: 110/120 - 🚀 Pegando ritmo
Day 07: 98/120 - 🎊 Primeira semana completa!
```

---

## 6️⃣ ROTINA SEMANAL (30 min - Todo domingo)

### Checklist Semanal

```bash
# 1. Abra `/reviews/Week_X_Review.md`
# 2. Preencha análise (veja template em TEMPLATES.md)
# 3. Analise padrões
# 4. Ajuste estratégia se necessário

# 5. Commit:
git add reviews/Week_X_Review.md
git commit -m "Week X Review: [pontos total]/840 - [insight]"
git push
```

### Atualizar `/statistics/burndown.md`

```markdown
# 📈 Progresso Semanal

## Semana X

| Dia | Pontos | Streak 🔥 | Cumprimento |
|-----|--------|-----------|-------------|
| Seg | 115 | 1 | 96% |
| Ter | 105 | 2 | 88% |
| Qua | 120 | 3 | 100% |
| Qui | 95 | 4 | 79% |
| Sex | 110 | 5 | 92% |
| Sab | 100 | 6 | 83% |
| Dom | [review] | [review] | [review] |

**Total:** ___ / 840
**Trend:** ↑ Melhorando
```

---

## 7️⃣ ROTINA MENSAL (1 hora - Fim de cada ciclo)

### Checklist Mensal (Dias 30, 60, 90)

```bash
# 1. Abra `/reviews/Month_X_Review.md`
# 2. Preencha análise completa (veja template)
# 3. Compare ciclos
# 4. Prepare próximo ciclo

# 5. Commit:
git add reviews/Month_X_Review.md metas/Ciclo_[X+1]_Metas.md
git commit -m "Ciclo X COMPLETO: ___/3600 - 🏆 [achievement]"
git push
```

### Visualizações Opcionais

Se quiser gráficos lindos no GitHub:

**A. Criar `README_PROGRESS.md`**
```markdown
# 📊 Progresso em Tempo Real

![Burndown Chart](https://img.shields.io/badge/Dias-XX/90-blue)
![Pontos](https://img.shields.io/badge/Pontos-XXX/10800-green)
![Nível](https://img.shields.io/badge/Nível-🦅-gold)

**Ciclo:** X/3
**Streak:** 🔥 XX dias
```

**B. Usar GitHub Actions** (avançado - cria commits automáticos)

---

## 8️⃣ DICAS DE WORKFLOW

### Terminal Simplificado

Crie um script `commit_day.sh`:

```bash
#!/bin/bash
# Uso: ./commit_day.sh 01 105 "🔥 Ótimo dia"

DAY=$1
PONTOS=$2
MSG=$3

git add days/Day_$DAY.md
git commit -m "Day $DAY: $PONTOS/120 - $MSG"
git push
```

Uso:
```bash
chmod +x commit_day.sh
./commit_day.sh 01 105 "🔥 Ótimo dia"
```

### GitHub Projects (Rastreamento Visual)

1. Vá ao seu repositório
2. Aba **Projects** → **New project**
3. Tipo: **Table** (melhor para isso)
4. Crie colunas:
   - Status (Not started, In progress, Done)
   - Pilar (Saúde, Finanças, etc)
   - Pontos
   - Data

5. Adicione issues/tasks para cada semana

### GitHub Discussions (Comunidade)

1. Habilite **Discussions** nas settings do repo
2. Crie categoria "Wins" para celebrar
3. Compartilhe progresso (opcional)

---

## 9️⃣ MELHORIAS VISUAIS

### Add Badge no README

```markdown
# 90D Protocolo de Mudança de Vida

![Status](https://img.shields.io/badge/Status-Em%20progresso-blue)
![Dia](https://img.shields.io/badge/Dia-XX%2F90-green)
![Nível](https://img.shields.io/badge/Nível-🌿-brightgreen)
![Streak](https://img.shields.io/badge/Streak-🔥%20XX%20dias-red)

**Total de Pontos:** XXX / 10.800
```

### Emojiis que funcionam bem

- 🔥 Streak
- 🎯 Meta
- ✅ Completo
- ⚠️ Parcial
- ❌ Falhado
- 🚀 Aceleração
- 📈 Progresso
- 🏆 Win
- 💪 Força
- 🌿 Crescimento

---

## 🔟 COMEÇAR - CHECKLIST FINAL

- [ ] Repositório criado no GitHub
- [ ] Estrutura de pastas criada
- [ ] README.md customizado
- [ ] PROTOCOLO.md copiado
- [ ] METAS Ciclo 1 customizadas
- [ ] Dia 1 preparado (`days/Day_01.md`)
- [ ] `statistics/stats.json` inicial preenchido
- [ ] Primeiro commit feito: `git commit -m "Start 90D Challenge - Day 0"`
- [ ] Compartilhado com accountability partner (opcional)

---

## 🚀 COMEÇAR AGORA

**Hoje - Antes de dormir:**
1. Criar repositório no GitHub (5 min)
2. Fazer upload de arquivos (10 min)
3. Preencher `Day_01.md` para amanhã (5 min)
4. First commit 🎊

**Amanhã - Dia 1:**
1. Acordar e executar metas
2. Noite: Preencher `Day_01.md`
3. Fazer commit
4. Dormir sabendo que começou! 🚀

---

## 💬 SUPORTE & TROUBLESHOOTING

### Git: "fatal: not a git repository"
```bash
cd seu-projeto
git init
git remote add origin https://github.com/...
```

### Esqueci de fazer commit
```bash
# Recupera arquivos não enviados
git status

# Adiciona tudo
git add .
git commit -m "Catch-up: Days XX-XX"
git push
```

### Quero resetar um dia
```bash
# Ver histórico
git log

# Reverter último commit (sem perder arquivo)
git reset --soft HEAD~1
```

---

## 🎊 PRONTO!

Você tem tudo que precisa. **Agora é com você!**

- Repositório estruturado ✅
- Protocolo detalhado ✅
- Templates prontos ✅
- Guia de setup ✅

**Falta apenas COMEÇAR.**

> "O melhor momento para começar foi ontem. O segundo melhor é agora." 🚀

---

**Commit final:** `git commit -m "Setup completo - Let's go! 🚀🚀🚀"`

---

*Atualizado: 2026-09-05*

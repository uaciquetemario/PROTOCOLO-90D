# 🚀 Protocolo de 90 Dias - Mudança de Vida

**Objetivo:** Evoluir em 5 pilares através de metas progressivas, check-ins diários e revisões estruturadas.

**Duração:** 90 dias = 3 ciclos de 30 dias (cada ciclo aumenta em dificuldade)  
**Formato:** Rastreamento diário + Revisões semanais + Análise mensal + Gamificação

---

## 📊 Os 5 Pilares

| Pilar | Descrição | Meta do Ciclo 1 |
|-------|-----------|-----------------|
| 💪 **SAÚDE** | Fitness, nutrição, sono, energia | Exercício 4x/sem + Nutrição consciente |
| 💰 **FINANÇAS** | Renda, gastos, investimentos, independência | Reduzir gastos + Criar fluxo extra |
| 🧘 **ESPIRITUALIDADE** | Meditação, propósito, reflexão, fé | 10 min meditação diária + Journaling |
| 💬 **RELACIONAMENTOS** | Conexões, família, networking, qualidade | 1 conversão profunda por semana |
| 🧠 **DESENVOLVIMENTO PESSOAL** | Aprendizado, habilidades, mentalidade | 1h estudo diário + Implementar 1 habilidade |

---

## 📈 Estrutura dos 3 Ciclos

### **Ciclo 1 (Dias 1-30): FUNDAÇÃO** ✅
- Metas: Base simples e factíveis
- Foco: Criar hábitos
- Dificuldade: ⭐⭐ (2/5)

### **Ciclo 2 (Dias 31-60): PROGRESSÃO** 📈
- Metas: Aumentar 30% de dificuldade
- Foco: Consolidar + adicionar novos desafios
- Dificuldade: ⭐⭐⭐ (3/5)

### **Ciclo 3 (Dias 61-90): DOMÍNIO** 💎
- Metas: Aumentar 60% de dificuldade do ciclo 1
- Foco: Excelência e resultados visíveis
- Dificuldade: ⭐⭐⭐⭐ (4/5)

---

## 🎮 Sistema de Gamificação

### Pontuação Diária
- ✅ Meta completa: **+10 pontos**
- ⚠️ Meta parcial (50-99%): **+5 pontos**
- ❌ Meta não cumprida: **0 pontos**
- 🔥 Streak de 7 dias: **+20 bônus**
- 💎 Streak de 30 dias: **+50 bônus**

### Níveis de Progresso
| Pontos | Nível | Badge |
|--------|-------|-------|
| 0-300 | 🥚 Iniciante | Egg |
| 301-600 | 🌱 Germinando | Sprout |
| 601-1000 | 🌿 Crescendo | Growing |
| 1001-1500 | 🌳 Florescendo | Blooming |
| 1501+ | 🦅 Dominador | Master |

### Metas Bônus
- Sem pular nenhum dia no mês: **+100 pontos**
- Completar 100% de um pilar em 7 dias: **+50 pontos**
- Fazer reflexão mensal completa: **+30 pontos**

---

## 📋 Sistema de Rastreamento

### Diário
```
Formato: /days/Day_XX.md

✅ SAÚDE
- [ ] Exercício (tipo: __)
- [ ] Nutrição consciente
- [ ] 8h de sono
- Pontos: _/30

✅ FINANÇAS
- [ ] Registrar gastos
- [ ] Meta específica: __
- Pontos: _/30

✅ ESPIRITUALIDADE
- [ ] Meditação 10min
- [ ] Journaling/Reflexão
- Pontos: _/20

✅ RELACIONAMENTOS
- [ ] Conexão qualidade
- [ ] 1 mensagem genuína
- Pontos: _/20

✅ DESENVOLVIMENTO
- [ ] Estudo 1h
- [ ] Implementação/Prática
- Pontos: _/20

Total do Dia: ___/120 | Streak: 🔥 __
```

### Semanal (Todo domingo)
```
Formato: /reviews/Week_X_Review.md

📊 Semana X (Dias XX-XX)
Pontos totais: ___
Melhor dia: __ (___pontos)
Pilar mais forte: __
Pilar com dificuldade: __

🎯 Reflexões:
- O que funcionou bem?
- Onde tive dificuldades?
- Qual aprendizado levo?
- Ajustes para próxima semana?

💪 Wins da semana:
- [ ] Win 1
- [ ] Win 2
```

### Mensal (Fim de cada ciclo)
```
Formato: /reviews/Month_X_Review.md

📈 CICLO X COMPLETO
Total de pontos: ___
Nível atingido: __
Streaks alcançados: __

Análise por pilar:
- SAÚDE: ___% cumprimento | Evolução: ↑↓→
- FINANÇAS: ___% cumprimento | Evolução: ↑↓→
- ESPIRITUALIDADE: ___% cumprimento | Evolução: ↑↓→
- RELACIONAMENTOS: ___% cumprimento | Evolução: ↑↓→
- DESENVOLVIMENTO: ___% cumprimento | Evolução: ↑↓→

🏆 Maiores achievements do mês:
1. __
2. __
3. __

📝 Lições aprendidas:
- __

🎯 Ajustes para próximo ciclo:
- __

💡 Previsão do ciclo seguinte:
- Metas serão: __% mais desafiadoras
```

---

## 🗂️ Estrutura do Repositório

```
90-dias-mudanca-vida/
├── README.md (este arquivo)
├── PROTOCOLO.md (guia detalhado)
├── METAS/
│   ├── Ciclo_1_Metas.md
│   ├── Ciclo_2_Metas.md
│   └── Ciclo_3_Metas.md
├── days/
│   ├── Day_01.md
│   ├── Day_02.md
│   └── ... (até Day_90)
├── reviews/
│   ├── Week_1_Review.md
│   ├── Week_2_Review.md
│   ├── ... (até Week_13)
│   ├── Month_1_Review.md
│   ├── Month_2_Review.md
│   ├── Month_3_Review.md
│   └── FINAL_90D_REVIEW.md
├── statistics/
│   ├── stats.json (dados para gráficos)
│   └── burndown.md (progresso visual)
└── templates/
    ├── daily_template.md
    ├── weekly_template.md
    └── monthly_template.md
```

---

## 🚀 Como Usar

### Dia 1
1. Clone/crie este repositório
2. Revise as metas de cada pilar
3. Preencha `Day_01.md` com check-ins
4. Faça commit: `git add . && git commit -m "Day 1: Starting 90D Challenge"`

### Rotina Diária
1. Abra o arquivo do dia (`/days/Day_XX.md`)
2. Registre as metas completadas (✅) ou incompletas (❌)
3. Calcule os pontos do dia
4. Mantenha o streak contando

### Toda Semana (Domingo)
1. Preencha `/reviews/Week_X_Review.md`
2. Analise padrões
3. Ajuste estratégia se necessário
4. Commit: `git add . && git commit -m "Week X Review Complete"`

### Final de Cada Ciclo (Dias 30, 60, 90)
1. Preencha a review mensal
2. Compare com ciclo anterior
3. Prepare metas para próximo ciclo (aumente dificuldade +30%)
4. Commit: `git add . && git commit -m "Ciclo X COMPLETO - X pontos"`

---

## 📊 Visualizações & Métricas

### Dashboard Básico (em `statistics/stats.json`)
```json
{
  "day": 1,
  "total_points": 105,
  "streak": 1,
  "pillar_progress": {
    "saude": 90,
    "financas": 100,
    "espiritualidade": 95,
    "relacionamentos": 100,
    "desenvolvimento": 80
  },
  "weekly_total": 105
}
```

### Gráficos Sugeridos
- 📈 Burndown: pontos acumulados vs meta
- 📊 Heatmap: atividade diária (como GitHub)
- 🎯 Radar Chart: performance por pilar
- 📉 Tendência: progresso ao longo dos 90 dias

---

## 💡 Dicas de Sucesso

✨ **Pequenos passos:** Comece fácil no ciclo 1  
✨ **Consistência:** 1 dia ruim ≠ falha do protocolo  
✨ **Flex:** Se errou um dia, volta no próximo  
✨ **Comunidade:** Compartilhe progresso (opcional)  
✨ **Reflexão:** As reviews semanais/mensais são CRÍTICAS

---

## 🔥 Inspiração

**Dias 1-30:** "Estou criando a base"  
**Dias 31-60:** "Estou acelerando"  
**Dias 61-90:** "Estou transformando"  

> "Você não sobe uma montanha em um dia. Mas se subir um pequeno degrau a cada dia, em 90 dias estará no topo."

---

## 📝 Começar Agora

Próximo passo: Revise `PROTOCOLO.md` para guia detalhado das metas.

**Let's go! 🚀**

---

*Atualizado: 2026-09-05*

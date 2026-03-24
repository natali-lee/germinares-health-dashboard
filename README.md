# Germinares Health Dashboard

Dashboard de análise de produtividade dos Germinares PicPay baseado em dados do Jira e GitHub.

## 📊 [Ver Dashboard](https://natali-lee.github.io/germinares-health-dashboard/)

## Métricas

**Health Score (0-100)** baseado em 6 dimensões:
- 📦 **Entrega** (25%): Issues done + PRs merged
- ⚡ **Eficiência** (20%): Cycle time em dias
- 📅 **Consistência** (15%): Semanas ativas
- 🔥 **Atividade** (15%): Dias desde última ação
- ✅ **Qualidade** (15%): Completion rate + aging
- 📊 **WIP** (10%): Carga de trabalho simultânea

## Dados

- **2.592 issues** analisadas (Jira)
- **178 PRs** analisados (GitHub)
- **216 Germinares** avaliados
- **Período**: últimos 30 dias
- **Atualização**: manual (sob demanda)

## Resumo

- 🟢 **11 Saudáveis** (80+ pontos)
- 🟡 **47 Atenção** (60-79 pontos)  
- 🔴 **158 Risco** (<60 pontos, inclui 41 inativos)

## Limitações

- GitHub: apenas 39/216 mapeados (username não segue padrão do email)
- Score reflete **atividade no período**, não competência
- Contexto importa: score baixo pode ser onboarding, férias, realocação

---

*Gerado por Wolf 🐺 · Data: 24/03/2026*
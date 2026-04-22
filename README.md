# Starian · Dashboard de Gestão de Problemas ITIL

Dashboard web para análise e diagnóstico de problemas ITIL Nível 3, desenvolvido para a equipe de operações da Starian.

## Acesso

🔗 [Abrir Dashboard](https://vrluz.github.io/dashboard-Ger.Problemas/)

## Como atualizar os dados

1. Exporte o relatório CSV do **Freshdesk**
2. Renomeie o arquivo para `dados.csv`
3. Faça o upload do arquivo neste repositório (substituindo o anterior)
4. Aguarde ~1 minuto — o dashboard será atualizado automaticamente para todos os usuários

## Funcionalidades

- **Dashboard** — Gráfico de eficácia de resolução por tipo
- **Matrizes** — Tabulação cruzada entre causa, solução e time
- **Reincidentes** — Top 20 assuntos com maior recorrência
- **Listagem** — Tabela completa de tickets com filtros
- **Painel ITIL** — Auditoria de qualidade e saúde operacional
- **Abertura de Problemas** — Candidatos a RCA (contorno / não resolvidos)

## Filtros disponíveis

Período, Empresa, Time de Desenvolvimento, Tipo de Pedido, Tipo de Resolução, Prioridade e Status.

## Tecnologias

HTML · CSS · JavaScript · Chart.js — sem dependências de servidor.

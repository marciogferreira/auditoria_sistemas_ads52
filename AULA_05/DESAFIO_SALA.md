
---

## 📘 Atividade Prática: Teste de Logs e Análise de Eventos

**Objetivo:**
Capacitar os alunos a identificar inconsistências, comportamentos suspeitos e falhas de controle por meio da análise de logs de sistema, aplicando técnicas de auditoria em registros de eventos.

---

### 📂 Cenário Simulado

A empresa fictícia **InfoSegur Ltda.** contratou você como auditor para revisar os **logs de acesso ao sistema** e verificar possíveis falhas de segurança, acessos indevidos ou violações de políticas internas.

Você receberá um **arquivo de log simulado** com registros de acessos ao sistema.

---

### 📝 Material a ser entregue aos alunos:

**Exemplo de Log Simulado (trecho):**

```txt
[2025-05-13 02:14:10] LOGIN SUCCESS - user: carlos.oliveira - IP: 192.168.0.12
[2025-05-13 02:15:03] FILE ACCESSED - user: carlos.oliveira - file: folha_pagamento.xls
[2025-05-13 09:05:44] LOGIN FAILURE - user: joana.lima - IP: 201.24.55.89
[2025-05-13 09:07:12] LOGIN SUCCESS - user: joana.lima - IP: 201.24.55.89
[2025-05-13 09:10:42] FILE DELETED - user: joana.lima - file: contratos_2022.docx
[2025-05-13 10:45:00] LOGIN SUCCESS - user: admin - IP: 192.168.0.1
[2025-05-13 10:47:11] PASSWORD CHANGED - user: admin
[2025-05-13 11:00:00] LOGIN FAILURE - user: carlos.oliveira - IP: 190.85.20.101
[2025-05-13 11:00:10] LOGIN FAILURE - user: carlos.oliveira - IP: 190.85.20.101
[2025-05-13 11:00:21] LOGIN SUCCESS - user: carlos.oliveira - IP: 190.85.20.101
[2025-05-13 11:01:00] FILE ACCESSED - user: carlos.oliveira - file: dados_clientes.csv
```
---

### 👨‍🏫 Orientações para a Atividade (em grupo ou individual):

**Parte 1 – Leitura e interpretação:**

1. Identifique **ações suspeitas** no log.
2. Determine se há **indícios de violação de segurança** (ex: acesso fora do horário comercial, falhas repetidas de login, exclusões de arquivos, mudança de senha inesperada).
3. Liste **três hipóteses de incidentes** com base nos eventos.

**Parte 2 – Testes de Auditoria em Logs:**

1. Elabore **3 testes de auditoria** que podem ser aplicados aos logs.

   * Exemplo: “Verificar tentativas de acesso malsucedidas fora do IP interno da empresa.”
2. Aponte os **controles que deveriam estar ativos** para evitar os incidentes identificados.

**Parte 3 – Relatório de Achados:**

* Produza um **mini-relatório (1 página)** com:

  * Resumo das irregularidades encontradas
  * Testes realizados
  * Recomendações de melhoria

---

### 🕒 Duração Sugerida:

* 20 min – Leitura e análise dos logs
* 30 min – Elaboração dos testes e relatório
* 10 min – Apresentação (opcional, para 1 ou 2 grupos)
* 5 min – Discussão geral sobre a importância da análise de logs

---

### ✅ Avaliação Sugerida:

| Critério                              | Pontos     |
| ------------------------------------- | ---------- |
| Identificação de anomalias            | 3 pts      |
| Criatividade e coerência dos testes   | 3 pts      |
| Clareza e organização do relatório    | 2 pts      |
| Recomendações técnicas e operacionais | 2 pts      |
| **Total**                             | **10 pts** |

---

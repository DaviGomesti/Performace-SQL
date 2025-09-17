# ⚡ Performance-SQL  

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Database](https://img.shields.io/badge/Database-Estatísticas-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Em%20Estudo-yellow?style=for-the-badge)

---

## 📌 Sobre o Repositório  

Este repositório contém **scripts de estudo e práticas de performance no SQL Server**, com foco em **estatísticas, índices e planos de execução**.  

O objetivo é entender como o otimizador de consultas do SQL Server utiliza as estatísticas para gerar planos eficientes e como diferentes configurações impactam no desempenho.  

---

## 📂 Estrutura do Repositório  

- **📄 create_database.sql** → Criação do banco `ESTATISTICAS`  
- **📄 create_tables.sql** → Criação das tabelas `PESSOAS` e `ENDERECOS` com constraints  
- **📄 insert_data.sql** → Inserção de 100.000 registros para simulação de cenários reais  
- **📄 stats_management.sql** → Exemplos de consulta, criação, atualização e exclusão de estatísticas  
- **📄 execution_plans.sql** → Consultas para verificar planos de execução com e sem estatísticas  
- **📄 update_stats.sql** → Atualização de estatísticas (`sp_updatestats`, `UPDATE STATISTICS` e `FULLSCAN`)  

---

## 🔑 Conceitos Abordados  

- ✅ Criação e gerenciamento de **estatísticas no SQL Server**  
- ✅ Uso de **constraints** (PK, FK, Unique, Check)  
- ✅ Diferença entre **AUTO_CREATE_STATISTICS ON/OFF**  
- ✅ Impacto da ausência de estatísticas no **plano de execução**  
- ✅ Consultas para **analisar estatísticas com `DBCC SHOW_STATISTICS`**  
- ✅ Atualização de estatísticas com `SP_UPDATESTATS` e `UPDATE STATISTICS`  
- ✅ Criação e exclusão manual de estatísticas  

---

## 🚀 Como Usar  

1. Clone este repositório:  
   ```bash
   git clone https://github.com/seu-usuario/Performace-SQL.git
   cd Performace-SQL

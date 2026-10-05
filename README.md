# -Criando-Transa-es-Executando-Backup-e-Recovery-de-Banco-de-Dados
Projeto DIO - SQL

# Desafio DIO - Transações, Procedures e Backup

## Descrição

Projeto desenvolvido para demonstrar o uso de transações, controle de erros em procedures e estratégias de backup e recuperação de bancos de dados MySQL.

---

# Parte 1 - Transações

Foram implementadas transações utilizando:

* START TRANSACTION
* COMMIT
* ROLLBACK

Objetivo:

Garantir integridade dos dados durante operações críticas.

---

# Parte 2 - Procedure com Transação

Foi criada uma Stored Procedure contendo:

* Controle transacional
* Tratamento de exceções
* ROLLBACK automático
* SAVEPOINT para recuperação parcial

Benefícios:

* Maior segurança
* Menor risco de inconsistência
* Controle refinado de falhas

---

# Parte 3 - Backup e Recovery

Foram realizados backups utilizando o utilitário mysqldump.

## Recursos incluídos

* Tabelas
* Views
* Procedures
* Triggers
* Eventos

## Comandos Utilizados

### Backup

mysqldump -u root -p ecommerce > ecommerce_backup.sql

### Recovery

mysql -u root -p ecommerce < ecommerce_backup.sql

---

# Conceitos Aplicados

* ACID
* Transações
* COMMIT
* ROLLBACK
* SAVEPOINT
* Stored Procedures
* Backup
* Recovery
* Administração de Banco de Dados (DBA)

## Autor

Tiago Alves

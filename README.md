# 🇷🇼 ProjectRwanda SACCO - Database Administration System

## 📌 Project Overview
**ProjectRwanda SACCO (Savings and Credit Cooperative)** is a robust relational database management system designed to securely track member profiles, savings accounts, credit loans, installment repayments, internal staff roles, and audit trails. 

This repository emphasizes core **Database Administration (DBA)** principles, including:
* **Role-Based Access Control (RBAC):** Least-privilege user permissions for Tellers, Managers, and DBAs.
* **Performance Optimization:** Strategic indexing on high-frequency search columns (`NationalID`, `AccountNumber`).
* **Data Integrity & Security:** ACID-compliant transactions and automated audit logging.

---

## 🗂️ Repository Structure
```text
projectrwanda-sacco-dba/
├── sql/
│   ├── 01_schema.sql         # DDL core tables, foreign keys, and CHECK constraints
│   ├── 02_security_rbac.sql  # User roles and least-privilege permission grants
│   └── 03_indexing_audit.sql # Performance indexes and DBA audit log triggers
├── diagrams/
│   └── sacco_erd.png         # Master Entity-Relationship Diagram (ERD)
├── docs/
│   └── test_execution.md     # Proof of transaction testing and backup logs
└── README.md                 # Project documentation

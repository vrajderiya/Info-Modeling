# 🧭 Travel Reimbursement Knowledge Graph (Neo4j)

![Neo4j Badge](https://img.shields.io/badge/Database-Neo4j-blue?style=for-the-badge&logo=neo4j)
![License Badge](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status Badge](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Language Badge](https://img.shields.io/badge/Language-Cypher-lightgrey?style=for-the-badge&logo=neo4j)

---

<p align="center">
  <img src="assets/banner.png" alt="Project Banner" width="90%">
  <br>
  <em>Graph-based modeling of university travel reimbursement workflow</em>
</p>

---

## 🧠 Overview
This project models the **University Travel Reimbursement process** using **Neo4j**, a graph database built for relationship-driven analytics.  
It demonstrates how financial and administrative entities interact across multiple hierarchical layers of approval, auditing, and reimbursement.  

With this graph model, users can visualize how **Travelers**, **Departments**, and **Financial Offices** interconnect, enabling data-driven analysis of workflow efficiency and compliance.

---

## ⚙️ Key Features
- Constructed a **Neo4j-based graph model** using Cypher queries and dataset imports (CSV).  
- Modeled **real-world entities** – Traveler, Department, Financial Services, and Policy.  
- Implemented relationship types like `REQUESTS`, `AUDITS`, `APPROVES`, and `REIMBURSES`.  
- Solved **cross-platform CSV ingestion issues** (Windows vs macOS compatibility).  
- Designed **queries and patterns** to analyze workflow dependencies and bottlenecks.

---

## 🧩 Data Model Overview
| **Entity** | **Core Attributes** | **Relationships** |
|-------------|--------------------|-------------------|
| Traveler | TravelID, Name, Email, SSN, TypeOfTraveler | REQUESTS → Reimbursement |
| Reimbursement | TravelID, Amount, Documents | AUDITED BY, APPROVED BY, REIMBURSED BY |
| Department Administrator | Name, UIN | AUDITS → Reimbursement |
| Budget Office | DepartmentID, Location, BudgetAllocation | APPROVES → Reimbursement |
| University Financial Services | Officer, TransactionType, Account | REIMBURSES → Reimbursement |
| Policy | PolicyID, Description | GOVERNED_BY → Reimbursement |

---

## 🧰 Tech Stack
| Component | Technology |
|------------|-------------|
| Database | Neo4j |
| Query Language | Cypher |
| Data Sources | CSV Files |
| Schema Design | Draw.io |
| Visualization | Neo4j Browser / Bloom |

---

## 🚀 Setup Instructions

### Prerequisites
- [Neo4j Desktop](https://neo4j.com/download/) or [Neo4j Aura Cloud](https://neo4j.com/cloud/aura/)
- Basic understanding of Cypher Query Language
- CSV data in the `import` folder

### Steps

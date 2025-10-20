# 🧭 Travel Reimbursement Knowledge Graph

An interactive Neo4j graph database project modeling a university travel reimbursement workflow. This project uses Cypher queries and CSV data files to build and analyze relationships between travelers, departments, administrators, budget offices, and financial services.

---

## 📊 Getting Started

> Launch Neo4j Desktop or Aura, then run Cypher scripts located in the `queries/` folder to create nodes, load data from CSVs in `data/`, and model relationships.

---

## 🧰 Features

* 📈 Graph-based modeling of travel reimbursement entities and workflows  
* 🗂️ Structured data import from CSV files to Neo4j  
* 🔍 Cypher queries enabling retrieval of request approvals, audit trails, and reimbursement amounts  
* 🏛️ Enforces organizational policies and compliance conditions  
* 💾 Includes ER diagram and detailed entity relationships in reimbursements and approvals  

---

## 🗂️ Project Structure

```
Info-Modeling/
│
├── data/                         # CSV files for graph import
├── queries/                      # Cypher scripts for schema and data loading
├── diagrams/                     # ER diagrams (Draw.io/PDF)
├── reports/                      # Memos and project documentation
├── README.md                     # Project overview and instructions
└── LICENSE                       # MIT License
```

---

## ⚙️ Installation & Running

1. **Clone the repository:**

git clone https://github.com/vrajderiya/Info-Modeling.git
cd Info-Modeling


2. **Start Neo4j Desktop or connect to Neo4j Aura.**

3. **Place CSV files from `data/` into Neo4j import directory.**

4. **Run Cypher scripts in `queries/` to create and populate the graph.**

5. **Explore the data and relationships using Neo4j Browser or Bloom.**

---

## 📚 Dataset

The project models data about university travelers (students and employees), reimbursement requests, approval workflows, auditing steps, budgeting department inputs, and university financial services processing—all simulated via CSV files.

---

## 📸 Screenshots

[Group_06-ER-Diagram.drawio.pdf](https://github.com/user-attachments/files/22995502/Group_06-ER-Diagram.drawio.pdf)


---

## 🪪 License

This project is licensed under the **MIT License**. Feel free to modify, use, and distribute it with attribution.

---

## 🙋‍♂️ Author

Developed by **[Vraj Deriya](https://github.com/vrajderiya)**  
For feedback or collaboration, reach out via GitHub.


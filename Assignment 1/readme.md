# Assignment 1: Conceptual Modeling and Relational Schema Blueprinting 

## 1. Assignment Summary
This foundational assignment explored the initial engineering stages of database creation—transforming real-world unstructured application requirements into precise database designs. The project focused on mastering entity relationship mapping and constraints modeling. Working across distinct retail, research, and corporate data problem sets, I designed structural schemas using both **Chen's Notation** and **Crow's Foot Notation**. The final components required translating abstract conceptual architectures into structural relational schemas while establishing strict integrity constraints through primary key and foreign key mapping definitions.

---

## 2. Reflection

### What I Learned
* Mapping abstract business logic into precise Chen and Crow's Foot notations showed me that database engineering starts long before writing code. I learned how crucial it is to define exact structural boundaries and relationships up front to avoid structural issues later.
* Figuring out entity integrity parameters and tracing primary-to-foreign key connections gave me a solid grasp of relational mechanics. It helped me see how individual data sheets link up into a unified database ecosystem.
* Translating conceptual schemas into production-ready relational layouts taught me how to map out multi-table dependencies. Learning to explicitly model foreign key points ensured complete lookup reliability between connected tables.

### Areas for Improvement
* On complex relationship maps with multiple many-to-many conditions, tracking individual connector paths can become disorganized. I want to work on grouping overlapping attribute arrays more cleanly to make large conceptual diagrams easier to read.
* While standard key assignments handle typical integrity conditions well, I plan to research custom business check constraints to implement automated domain-level data filters directly within the table definitions.

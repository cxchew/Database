# Lab Activity 2: Relational Data Retrieval and Multi-Table SQL Engineering

## 1. Lab Summary
This comprehensive hands-on lab activity involved the systematic construction, validation, and debugging of Structured Query Language (SQL) statements to extract targeted intelligence from a relational data model. The engineering playground simulated a production-grade online bookstore infrastructure containing four deeply interconnected core entity schemas: `books` (catalog parameters), `customers` (registration metadata), `orders` (transactional lifecycle mapping), and `order_items` (many-to-many lookup resolution intersections). 

The underlying objective was to translate complex, multi-variable real-world business scenarios into clean, highly optimized Data Manipulation Language (DML) query code. The task required working extensively with foundational logical structural blocks, deploying precise target row filters, mapping cross-entity relational paths via internal joins, and applying mathematical aggregation matrices. By troubleshooting performance barriers and resolving analytical query logic requests, I successfully built and tested a sequence of advanced operations capable of distilling messy database data arrays into clean, actionable analytical records.

---

## 2. Reflection

### What I Learned
* Writing multi-table join statements completely changed how I think about data retrieval. Seeing how separate files link up to reveal complete customer buying patterns showed me the real analytical power of SQL.
* Learning the difference between standard filters and post-aggregation filters was a major milestone. I realized that using `WHERE` to narrow down raw rows before using `HAVING` to clean up grouped summaries is key to writing fast, accurate queries.
* Translating everyday business questions into clean code blocks sharpened my analytical thinking. It proved that retrieving targeted database information relies on setting up precise logical paths.

### Areas for Improvement
* As data requests require more table joins, the code can quickly become long and difficult to scan. I need to practice using clear table aliases and structured indentations to keep complex queries clean and maintainable.
* I want to move past basic inner join queries and explore specialized retrieval methods. Learning to handle missing records using left/right outer joins and building nested subqueries will help me manage advanced report requests.

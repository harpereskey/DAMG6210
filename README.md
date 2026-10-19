# CareLedger: Massachusetts Health Network Database

A relational database for a healthcare management system, designed and implemented by a three person team for **DAMG 6210: Database Management and Database Design** at Northeastern University.

CareLedger models how patients, providers, organizations, encounters, and clinical records connect across a Massachusetts health network.

## Team

| Name | GitHub |
|---|---|
| Harper Eskey | [@harpereskey](https://github.com/harpereskey) |
| Eda Imer | |
| Khushi Trivedi | |

## Project goals

* Design a normalized relational model for a real world healthcare domain
* Move deliberately from conceptual model to logical model to physical implementation
* Populate and query the database with sample data that reflects realistic network activity
* Support the kinds of questions a health network actually asks: patient history, provider workload, encounter volume, and costs

## Design process

### 1. Conceptual model
Identified the core entities in a health network and how they relate, independent of any database technology.

### 2. Logical model (EER)
Translated the conceptual model into an Enhanced Entity Relationship (EER) model and normalized it to remove redundancy and update anomalies. Primary keys, foreign keys, and cardinalities are defined at this stage.

### 3. Implementation
Built the physical schema in SQL, populated it with sample data, and wrote queries to validate the design.

## Repository structure

```
DAMG6210/
├── docs/          # Conceptual and EER diagrams, design notes
├── sql/
│   ├── ddl/       # CREATE TABLE scripts
│   ├── dml/       # Sample data insert scripts
│   └── queries/   # Analysis and validation queries
└── README.md
```

## Getting started

```bash
git clone https://github.com/harpereskey/DAMG6210.git
cd DAMG6210
```

1. Run the scripts in `sql/ddl/` to create the schema
2. Run the scripts in `sql/dml/` to insert the sample data
3. Explore with the queries in `sql/queries/`

## Status

* [x] Conceptual model
* [x] Logical EER model
* [ ] Physical implementation and sample data
* [ ] Analysis queries
* [ ] Final report and presentation

## Acknowledgments

Built for DAMG 6210 at Northeastern University.

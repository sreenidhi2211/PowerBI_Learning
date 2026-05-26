# Phase 2 — Power Query (ETL)

**Phase Status:** ✅ Complete  
**Modules Covered:** Module 3  
**Dataset:** Superstore Sales (Single Excel Source — Orders, Returns, People sheets)

---

## Phase Overview

Phase 2 covers Power Query — Power BI's built-in data transformation engine. Raw data from a source is rarely clean or structured correctly for analysis. Power Query is where that data gets shaped before it enters the model.

This phase takes the Superstore initial 3 tables and transforms them into the individual tables that will form the star schema in Phase 3. Every transformation decision made here directly determines the quality and accuracy of the data model built in the next phase. A mistake in Power Query propagates silently into every DAX calculation and visual built on top of it.

---

## Modules in This Phase

### Module 3 — Data Transformation

Covers the full Power Query workflow applied to the Superstore Sales dataset. The flat Orders table is broken down into separate dimension tables in preparation for star schema modeling in Phase 3.

**Key concepts:** Duplicate vs Reference queries, custom columns, removing duplicates, data type verification, building a Date table using `List.Dates()`, loading the People and Returns tables.  
**Status:** ✅ Complete  
**Notes:** `Module-03-Data-Transformation/Module03-Notes.pdf`

---

## What This Phase Prepares

The transformations completed in this phase produce the following tables, which are handed directly to Phase 3 for relationship building:

| **Table** | **Type** | **Built From** |
| --- | --- | --- |
| Orders | Fact Table | Original Orders sheet — descriptive columns removed |
| Customer | Dimension Table | Duplicated from Orders |
| Products | Dimension Table | Duplicated from Orders |
| Location | Dimension Table | Duplicated from Orders — composite key added |
| Date | Dimension Table | Built from scratch using `List.Dates()` |
| People | Dimension Table | Loaded directly from People sheet |
| Returns | Bridge Table | Loaded directly from Returns sheet |

---

## Phase Structure

```
Phase-02-Power-Query-ETL/
├── README.md                     
└── Module-03-Data-Transformation/
    └── Module03-Notes.pdf
```

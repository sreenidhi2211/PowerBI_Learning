# Phase 4 — DAX (Data Analysis Expressions)

**Phase Status:** 🔄 In Progress  
**Modules Covered:** Module 5, Module 6, Module 7, Module 8  
**Dataset:** Superstore Sales (Single Excel Source — Orders, Returns, People sheets)

---

## Phase Overview

Phase 4 covers DAX — the formula language of Power BI. Every KPI, ratio, running total, and time-based comparison in a Power BI report is written in DAX. This phase builds DAX knowledge progressively, starting from the fundamentals and advancing to complex filter manipulation, time intelligence, and advanced functions.

---

## Modules in This Phase

### Module 5 — DAX Basics: Calculated Columns vs Measures

Covers the foundational concepts of DAX — syntax, functions, and context. Establishes the critical distinction between calculated columns and measures, and introduces the core aggregation, math, logical, and filter functions.

**Key concepts:** DAX syntax, row context vs filter context, calculated columns vs measures, aggregation functions, DIVIDE, IF, SWITCH, CALCULATE, FILTER, ALL, RELATED.  
**Status:** ✅ Complete  
**Notes:** `Module-05-DAX-Basics/Module-05-Notes.pdf`

---

### Module 6 — CALCULATE and Filter Context

Covers CALCULATE in depth — the most important function in DAX. Explores how filter context is created, modified, and overridden programmatically.

**Key concepts:** CALCULATE, filter context manipulation, ALL, ALLSELECTED, REMOVEFILTERS, context transition.  
**Status:**  ✅ Complete 
**Notes:** `Module-06-CALCULATE/Module-06-Notes.pdf`

---

### Module 7 — Time Intelligence Functions

Covers DAX functions that perform date-based calculations. Requires the dedicated Date table built in Phase 2.

**Key concepts:** TOTALYTD, TOTALQTD, SAMEPERIODLASTYEAR, DATEADD, DATESYTD, year-over-year comparisons.  
**Status:** ⏳ Pending  
**Notes:** `Module-07-Time-Intelligence/Module-07-Notes.pdf`

---

### Module 8 — Advanced DAX: RANKX, SWITCH, Variables

Covers advanced DAX patterns used in production reports — dynamic rankings, complex branching logic, and variable-based formulas for readability and performance.

**Key concepts:** RANKX, SWITCH, VAR, RETURN, iterator functions, advanced measure patterns.  
**Status:** ⏳ Pending  
**Notes:** `Module-08-Advanced-DAX/Module-08-Notes.pdf`

---

## Phase Structure

```
Phase-04-DAX/
├── README.md                        
├── Module-05-DAX-Basics/
│   └── Module-05-Notes.pdf
├── Module-06-CALCULATE/
│   └── Module-06-Notes.pdf
├── Module-07-Time-Intelligence/
│   └── Module-07-Notes.pdf
└── Module-08-Advanced-DAX/
    └── Module-08-Notes.pdf
```

---
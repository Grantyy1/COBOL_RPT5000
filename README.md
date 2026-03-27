# COBOL_RPT5000

## Introduction
This COBOL program generates a Year-To-Date Sales Report that compares each customer's sales figures from the current year against the previous year. It calculates the change in dollar amount and the percentage change between the two periods. The report is organised using a control break structure, producing subtotals at the sales representative level and the branch level, as well as a grand total across all branches.
The program outputs the following information in a formatted report:

The Branch Number
The Sales Rep Number
The Customer Number
The Customer Name
Sales Figure This Year (YTD)
Sales Figure Last Year (YTD)
Change in Amount
Change in Percentage
---

## 📑 Table of Contents
- [📌What does it do?](#What-does-it-do)
- [🖥️Output Code Example](#Output-of-the-code-running)
- [🛠️COBOL Concepts used](#COBOL-Concepts-covered-in-this-assignment-were)
- [👥Authors](#authors)
--- 
## What does it do?
  For each run, the program will:
  - 1. Calculates the sales difference between this year and last year.
  - 2. Calculates the amounts percentage increase or decrease.
  - 3. Outputs all of the customers information and sales amount information in a compreshensive report.

## Output of the code running:
```
DATE:  03/24/2026                YEAR-TO-DATE SALES REPORT                       PAGE:    1
TIME:  14:16                                                                        RPT3000
BRANCH  SALES CUST   SALES                    SALES         CHANGE        CHANGE
 NUM     REP   NUM   CUSTOMER NAME            THIS YTD      LAST YTD      AMOUNT       PERCENT
 12      12   11111  INFORMATION BUILDERS     1,234.56      1,111.11        123.45      11.1
         12   12345  CAREER TRAINING CTR     12,345.67     22,222.22      9,876.55-     44.4-
----------------------------------------------------------------------------------------------------------------------------------
                       BRANCH TOTAL   13,580.23     23,333.33      9,753.10-    41.8- *
----------------------------------------------------------------------------------------------------------------------------------
 22      10   22222  HOMELITE TEXTRON CO     34,545.00          0.00     34,545.00     999.9
         14   34567  NEAS MEMBER BENEFITS       111.11          0.00        111.11     999.9
         14   55555  PILOT LIFE INS. CO.     10,000.00      1,000.00      9,000.00     900.0
----------------------------------------------------------------------------------------------------------------------------------
                       BRANCH TOTAL   44,656.11      1,000.00     43,656.11    999.9  *
----------------------------------------------------------------------------------------------------------------------------------
 34      10   00111  DAUPHIN DEPOSIT BANK    14,099.00     19,930.00      5,831.00-     29.3-
         10   54321  AIRCRAFT OWNERS ASSC     5,426.12     40,420.00     34,993.88-     86.6-
         17   33333  NORFOLK CORP             6,396.35      4,462.88      1,933.47      43.3
----------------------------------------------------------------------------------------------------------------------------------
                       BRANCH TOTAL   25,921.47     64,812.88     38,891.41-    60.0- *
----------------------------------------------------------------------------------------------------------------------------------
 47      11   12121  GENERAL SERVICES CO.    11,444.00     11,059.56        384.44       3.5
         11   24680  INFO MANAGEMENT CO.     17,481.45     11,892.47      5,588.98      47.0
         21   99999  DOLLAR SAVINGS BANK      5,059.00      4,621.95        437.05       9.5
         21   76543  NATL MUSIC CORP.         2,383.46      4,435.26      2,051.80-     46.3-
----------------------------------------------------------------------------------------------------------------------------------
                       BRANCH TOTAL   36,367.91     32,009.24      4,358.67     13.6  *
----------------------------------------------------------------------------------------------------------------------------------
                       GRAND TOTAL:        ==========    ==========    ==========    ======= **
                                           120,525.72    121,155.45        629.73-      0.5-

```

## COBOL Concepts covered in this assignment were:
      - Program header level documentation.
      - Defining working storage data items.
      - Moving and computing values.
      - Displaying output code.
      - Adding branch subtotals.
      - Plus, creating a branch summary report.
      
---
## Authors

👨‍💻 **Grant Peverett**

- **Grant Peverett GitHub Profile**: [Grantyy1](https://github.com/Grantyy1)
  
- **Email**: [grpeve01@wsc.edu]

  
👨‍💻 **Kayley Wells**

- **Kayley Wells GitHub Profile**: [kayley-wells](https://github.com/kayley-wells)
  
- **Email**: [kawell03@wsc.edu]

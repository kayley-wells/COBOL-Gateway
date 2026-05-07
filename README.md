# COBOL Developer Gateway
- Author: Kayley Wells
- Course: Intro to Enterprise Computing

## About Me
I am currently studying Computer Information Systems - Networking & Cybersecurity at WSC. This repository is a portfolio of assignments and projects completed throughout my academic career.

## Profile

## Table of Contents
| Project Name | Coding Lanugage | Course | Description | Repository Link |
|---------|------|----------|-------------|------|
| [RPT2000](#RPT2000) | COBOL / JCL | Intro to Enterprise Computing | Batch reporting program that reads the Customer Master File and produces a formatted Year-to-Date Sales Report. | [RPT2000](https://github.com/kayley-wells/RPT2000) |
| [RPT3000](#RPT3000) | COBOL / JCL | Intro to Enterprise Computing | Calculates the amount changed for a customer's sales from the previous year compared to the present year. | [RPT3000](https://github.com/kayley-wells/RPT3000)|
| [RPT5000](#COBOL_RPT5000) | COBOL / JCL | Intro to Enterprise Computing | Generates a Year-To-Date Sales Report that compares each customer's sales figures from the current year against the previous year. | [RPT5000](https://github.com/Grantyy1/COBOL_RPT5000)|
| [RPT6000](#RPT6000) | COBOL / JCL | Intro to Enterprise Computing | Batch reporting program that reads the Customer Master File and Sales Rep Master File to produce a formatted Year-to-Date Sales Report. | [RPT6000](https://github.com/kayley-wells/RPT6000)|
| [CALC2000](#CALC2000) | COBOL / JCL | Intro to Enterprise Computing | Calculates the future value of an investment using a fixed annual interest rate over a fixed number of years. | [CALC2000](https://github.com/kayley-wells/CALC2000)|
| [SEQ3000](#SEQ3000) | COBOL / JCL | Intro to Enterprise Computing | A multi-program COBOL project designed to create, maintain, and update employee records using both sequential and indexed file processing techniques. | [SEQ3000](https://github.com/kayley-wells/SEQ3000)|
| [JAVAFXCalculator](#JAVAFXCalculator) | Java | Programming Fundamentals II | JavaFX-based application that allows users to interact with a calculator using the last user's entry or total using memory. | [JAVAFXCalculator](https://github.com/kayley-wells/JavaFXCalculator) |
| [MathTutorV6](#MathTutorV6) | C++ | Programming Fundamentals I | An interactive math tutor designed for young children. | [MathTutorV6](https://github.com/kayley-wells/MathTutorV6) |

## RPT2000
RPT2000 is a COBOL batch reporting program that reads the Customer Master File and produces a formatted Year-to-Date Sales Report. The report includes each customer's current and prior year sales figures, along with a calculated change amount and change percent for performance comparison.

Software Used:
- COBOL Enterprise
- VSCode
- GitHub

Output Example:
```
DATE:  04/10/2026                          YEAR-TO-DATE SALES REPORT                          PAGE:    1
TIME:  23:54                                                                                  RPT6000
                                                      SALES         SALES        CHANGE     CHANGE
BRANCH   SALESREP             CUSTOMER              THIS YTD      LAST YTD       AMOUNT     PERCENT
------ ------------- --------------------------   ------------  ------------   -----------  -------
  12   12 AJONES     11111 INFORMATION BUILDERS       1,234.56      1,111.11        123.45    +11.1
                     12345 CAREER TRAINING CTR       12,345.67     22,222.22      9,876.55-   -44.4

                                    SALESREP TOTAL  $13,580.23    $23,333.33     $9,753.10-   -41.8*

                                      BRANCH TOTAL  $13,580.23    $23,333.33     $9,753.10-   -41.8**

  22   10 UNKNOWN    22222 HOMELITE TEXTRON CO       34,545.00          0.00     34,545.00     N/A

                                    SALESREP TOTAL  $34,545.00         $0.00    $34,545.00     N/A *

       14 KBAKER     34567 NEAS MEMBER BENEFITS         111.11          0.00        111.11     N/A
                     55555 PILOT LIFE INS. CO.       10,000.00      1,000.00      9,000.00   +900.0

                                    SALESREP TOTAL  $10,111.11     $1,000.00     $9,111.11   +911.1*

                                      BRANCH TOTAL  $44,656.11     $1,000.00    $43,656.11   OVRFLW**

  34   10 UNKNOWN    00111 DAUPHIN DEPOSIT BANK      14,099.00     19,930.00      5,831.00-   -29.3
                     54321 AIRCRAFT OWNERS ASSC       5,426.12     40,420.00     34,993.88-   -86.6

                                    SALESREP TOTAL  $19,525.12    $60,350.00    $40,824.88-   -67.6*

       17 STRACKER   33333 NORFOLK CORP               6,396.35      4,462.88      1,933.47    +43.3

                                    SALESREP TOTAL   $6,396.35     $4,462.88     $1,933.47    +43.3*

                                      BRANCH TOTAL  $25,921.47    $64,812.88    $38,891.41-   -60.0**

  47   11 TSMITH     12121 GENERAL SERVICES CO.      11,444.00     11,059.56        384.44     +3.5
                     24680 INFO MANAGEMENT CO.       17,481.45     11,892.47      5,588.98    +47.0

                                    SALESREP TOTAL  $28,925.45    $22,952.03     $5,973.42    +26.0*

       21 FFRANKLIN  99999 DOLLAR SAVINGS BANK        5,059.00      4,621.95        437.05     +9.5
                     76543 NATL MUSIC CORP.           2,383.46      4,435.26      2,051.80-   -46.3

                                    SALESREP TOTAL   $7,442.46     $9,057.21     $1,614.75-   -17.8*

                                      BRANCH TOTAL  $36,367.91    $32,009.24     $4,358.67    +13.6**

                                       GRAND TOTAL $120,525.72   $121,155.45       $629.73-    -0.5***

```

## RPT3000
This COBOL program calculates the amount changed for a customer's sales from the previous year compared to the present year. It then subsequently calculates the percentage change as well.

Software Used:
- COBOL Enterprise
- VSCode
- GitHub

Output Example:
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

## RPT5000
This COBOL program generates a Year-To-Date Sales Report that compares each customer's sales figures from the current year against the previous year. It calculates the change in dollar amount and the percentage change between the two periods. The report is organised using a control break structure, producing subtotals at the sales representative level and the branch level, as well as a grand total across all branches.

Software Used:
- COBOL Enterprise
- VSCode
- GitHub

Output Example:
```
DATE:  03/31/2026                YEAR-TO-DATE SALES REPORT                       PAGE:    1
TIME:  13:51                                                                        RPT5000
BRANCH  SALES CUST   SALES                    SALES         CHANGE        CHANGE
 NUM     REP   NUM   CUSTOMER NAME            THIS YTD      LAST YTD      AMOUNT       PERCENT
------  ----- ----- ----------------------   ----------    ----------    ----------    -------
 12      12   11111  INFORMATION BUILDERS     1,234.56      1,111.11        123.45      11.1
 12      12   12345  CAREER TRAINING CTR     12,345.67     22,222.22      9,876.55-     44.4-
                              SALESREP TOTAL 13,580.23     23,333.33      9,753.10-    41.8-*
                              BRANCH TOTAL   13,580.23     23,333.33      9,753.10-    41.8-**
 
----------------------------------------------------------------------------------------------------------------------------------
 22      10   22222  HOMELITE TEXTRON CO     34,545.00          0.00     34,545.00     999.9
                              SALESREP TOTAL 34,545.00          0.00     34,545.00    999.9 *
 22      14   34567  NEAS MEMBER BENEFITS       111.11          0.00        111.11     999.9
 22      14   55555  PILOT LIFE INS. CO.     10,000.00      1,000.00      9,000.00     900.0
                              SALESREP TOTAL 10,111.11      1,000.00      9,111.11    911.1 *
                              BRANCH TOTAL   44,656.11      1,000.00     43,656.11    999.9 **
 
----------------------------------------------------------------------------------------------------------------------------------
 34      10   00111  DAUPHIN DEPOSIT BANK    14,099.00     19,930.00      5,831.00-     29.3-
 34      10   54321  AIRCRAFT OWNERS ASSC     5,426.12     40,420.00     34,993.88-     86.6-
                              SALESREP TOTAL 19,525.12     60,350.00     40,824.88-    67.6-*
 34      17   33333  NORFOLK CORP             6,396.35      4,462.88      1,933.47      43.3
                              SALESREP TOTAL  6,396.35      4,462.88      1,933.47     43.3 *
                              BRANCH TOTAL   25,921.47     64,812.88     38,891.41-    60.0-**
 
----------------------------------------------------------------------------------------------------------------------------------
 47      11   12121  GENERAL SERVICES CO.    11,444.00     11,059.56        384.44       3.5
 47      11   24680  INFO MANAGEMENT CO.     17,481.45     11,892.47      5,588.98      47.0
                              SALESREP TOTAL 28,925.45     22,952.03      5,973.42     26.0 *
 47      21   99999  DOLLAR SAVINGS BANK      5,059.00      4,621.95        437.05       9.5
 47      21   76543  NATL MUSIC CORP.         2,383.46      4,435.26      2,051.80-     46.3-
                              SALESREP TOTAL  7,442.46      9,057.21      1,614.75-    17.8-*
                              BRANCH TOTAL   36,367.91     32,009.24      4,358.67     13.6 **
 
----------------------------------------------------------------------------------------------------------------------------------
                         GRAND TOTAL:        ==========    ==========    ==========    =======***
                                             120,525.72    121,155.45        629.73-      0.5-
```
## RPT6000
RPT6000 is a COBOL batch reporting program that reads the Customer Master File and Sales Rep Master File to produce a formatted Year-to-Date Sales Report. The report includes each customer's current and prior year sales figures, along with a calculated change amount and change percent for performance comparison.

Software Used:
- COBOL Enterprise
- VSCode
- GitHub

Output Example:
```
DATE:  04/10/2026                          YEAR-TO-DATE SALES REPORT                          PAGE:    1
TIME:  23:54                                                                                  RPT6000
                                                      SALES         SALES        CHANGE     CHANGE
BRANCH   SALESREP             CUSTOMER              THIS YTD      LAST YTD       AMOUNT     PERCENT
------ ------------- --------------------------   ------------  ------------   -----------  -------
  12   12 AJONES     11111 INFORMATION BUILDERS       1,234.56      1,111.11        123.45    +11.1
                     12345 CAREER TRAINING CTR       12,345.67     22,222.22      9,876.55-   -44.4

                                    SALESREP TOTAL  $13,580.23    $23,333.33     $9,753.10-   -41.8*

                                      BRANCH TOTAL  $13,580.23    $23,333.33     $9,753.10-   -41.8**

  22   10 UNKNOWN    22222 HOMELITE TEXTRON CO       34,545.00          0.00     34,545.00     N/A

                                    SALESREP TOTAL  $34,545.00         $0.00    $34,545.00     N/A *

       14 KBAKER     34567 NEAS MEMBER BENEFITS         111.11          0.00        111.11     N/A
                     55555 PILOT LIFE INS. CO.       10,000.00      1,000.00      9,000.00   +900.0

                                    SALESREP TOTAL  $10,111.11     $1,000.00     $9,111.11   +911.1*

                                      BRANCH TOTAL  $44,656.11     $1,000.00    $43,656.11   OVRFLW**

  34   10 UNKNOWN    00111 DAUPHIN DEPOSIT BANK      14,099.00     19,930.00      5,831.00-   -29.3
                     54321 AIRCRAFT OWNERS ASSC       5,426.12     40,420.00     34,993.88-   -86.6

                                    SALESREP TOTAL  $19,525.12    $60,350.00    $40,824.88-   -67.6*

       17 STRACKER   33333 NORFOLK CORP               6,396.35      4,462.88      1,933.47    +43.3

                                    SALESREP TOTAL   $6,396.35     $4,462.88     $1,933.47    +43.3*

                                      BRANCH TOTAL  $25,921.47    $64,812.88    $38,891.41-   -60.0**

  47   11 TSMITH     12121 GENERAL SERVICES CO.      11,444.00     11,059.56        384.44     +3.5
                     24680 INFO MANAGEMENT CO.       17,481.45     11,892.47      5,588.98    +47.0

                                    SALESREP TOTAL  $28,925.45    $22,952.03     $5,973.42    +26.0*

       21 FFRANKLIN  99999 DOLLAR SAVINGS BANK        5,059.00      4,621.95        437.05     +9.5
                     76543 NATL MUSIC CORP.           2,383.46      4,435.26      2,051.80-   -46.3

                                    SALESREP TOTAL   $7,442.46     $9,057.21     $1,614.75-   -17.8*

                                      BRANCH TOTAL  $36,367.91    $32,009.24     $4,358.67    +13.6**

                                       GRAND TOTAL $120,525.72   $121,155.45       $629.73-    -0.5***
```

## CALC2000

## SEQ3000

## JAVAFXCalculator

## MathTutorV6

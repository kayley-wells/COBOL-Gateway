# COBOL Developer Gateway
- Author: Kayley Wells
- Course: Intro to Enterprise Computing

## About Me
I am currently studying Computer Information Systems - Networking & Cybersecurity at WSC. This repository is a portfolio of assignments and projects completed throughout my academic career.

## Profile
<p align="center">
  <img src="assets/profilepic.jpg" alt="Profile Picture" width="200"/>
</p>
<h3 align="center">Kayley Wells</h3>
<p align="center">
  <a href="https://github.com/kayley-wells">GitHub</a> •
  <a href="mailto:kawell03@wsc.edu">Email</a> •
  <a href="https://www.linkedin.com/in/kayley-wells-a2a503350/">LinkedIn</a>
</p>

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

✅ Completed
[RPT2000 Repository](https://github.com/kayley-wells/RPT2000)

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

[To Table of Contents](#table-of-contents)

## RPT3000
This COBOL program calculates the amount changed for a customer's sales from the previous year compared to the present year. It then subsequently calculates the percentage change as well.

Software Used:
- COBOL Enterprise
- VSCode
- GitHub

✅ Completed
[RPT3000 Repository](https://github.com/kayley-wells/RPT3000)

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

[To Table of Contents](#table-of-contents)

## RPT5000
This COBOL program generates a Year-To-Date Sales Report that compares each customer's sales figures from the current year against the previous year. It calculates the change in dollar amount and the percentage change between the two periods. The report is organised using a control break structure, producing subtotals at the sales representative level and the branch level, as well as a grand total across all branches.

Software Used:
- COBOL Enterprise
- VSCode
- GitHub

✅ Completed
[RPT5000 Repository](https://github.com/Grantyy1/COBOL_RPT5000)

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

[To Table of Contents](#table-of-contents)

## RPT6000
RPT6000 is a COBOL batch reporting program that reads the Customer Master File and Sales Rep Master File to produce a formatted Year-to-Date Sales Report. The report includes each customer's current and prior year sales figures, along with a calculated change amount and change percent for performance comparison.

Software Used:
- COBOL Enterprise
- VSCode
- GitHub

✅ Completed
[RPT6000 Repository](https://github.com/kayley-wells/RPT6000)

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

[To Table of Contents](#table-of-contents)
## CALC2000
A small COBOL program that calculates the future value of an investment using a fixed annual interest rateover a fixed number of years. After the first calculation, it doubles the investment amount twice, recalculating the future value each time.

Software Used:
- COBOL Enterprise
- VSCode
- GitHub

✅ Completed
[CALC2000 Repository](https://github.com/kayley-wells/CALC2000)

Output Example:
```
Calculating Future Values.
  ----------------------------
    Investment Amount =      1,000
    Number of Years   = 10
    Yearly Interest   = 5.5
    Future Value      =  1,708.16
  ----------------------------
  ----------------------------
    Investment Amount =      2,000
    Number of Years   = 10
    Yearly Interest   = 5.5
    Future Value      =  3,416.29
  ----------------------------
  ----------------------------
    Investment Amount =      4,000
    Number of Years   = 10
    Yearly Interest   = 5.5
    Future Value      =  6,832.58
  ----------------------------
```

[To Table of Contents](#table-of-contents)
## SEQ3000
The COBOL EMPLOYEE SYSTEM is a multi-program COBOL project designed to create, maintain, and update employee records using both sequential and indexed file processing techniques.

This system expands across multiple programs that work together to simulate real-world batch and online-style file maintenance. It includes initial file creation, sequential transaction processing, and indexed file maintenance with error handling. The programs demonstrate how employee data can be added, updated, deleted, and validated across different storage structures.

The system produces updated employee master files while also capturing invalid transactions for auditing and debugging purposes.

Software Used:
- COBOL Enterprise
- VSCode
- GitHub

✅ Completed
[SEQ3000 Repository](https://github.com/kayley-wells/SEQ3000)

Output Example for Employee File:
```
10008ROBERT DAVIS                  HR   H3065000{08003000
10012MARY WILLIAMS                 ACCT A1055000005002000
```

[To Table of Contents](#table-of-contents)
## JavaFXCalculator
The JavaFX Calculator is a JavaFX-based application that allows users to interact with a calculator using the last user's entry or total using memory. The application provides functionalities to add, multiply, divide, calculate exponents, and calculate square roots.

Software Used:
- IntelliJ IDEA
- Amazon Corretto
- Java 17
- GitHub

✅ Completed
[JavaFXCalculator Repository](https://github.com/kayley-wells/JavaFXCalculator)

Output Example:

<p align="left">
  <img src="assets/ex.gif" alt="JavaFXCalculator" />
</p>

[To Table of Contents](#table-of-contents)
## MathTutorV6
V6 is an interactive math tutor for young children that generates random math problems and dynamically adjusts difficulty based on the user's performance — leveling up with correct answers and down with incorrect ones. It collects the user's name, tracks their progress throughout the session, and provides encouraging feedback along the way. Once finished, the program displays a summary report showing which questions were answered correctly and incorrectly. It also supports saving and loading progress so users can pick up where they left off.

Software Used:
- CLion
- GitHub

✅ Completed
[MathTutorV6 Repository](https://github.com/kayley-wells/MathTutorV6)

Output Example:
```
************************************************************
 _   _      _        __       _   __  __       _   _
| | | | ___| |_ __  / _|_   _| | |  \/  | __ _| |_| |__
| |_| |/ _ \ | '_ \| |_| | | | | | |\/| |/ _` | __| '_ \
|  _  |  __/ | |_) |  _| |_| | | | |  | | (_| | |_| | | |
|_| |_|\___|_| .__/|_|  \__,_|_| |_|  |_|\__,_|\__|_| |_|
|_   _|   _| |_|___  _ __
  | || | | | __/ _ \| '__|
  | || |_| | || (_) | |
  |_| \__,_|\__\___/|_|
*************************************************************
*             Welcome to the Helpful Math Tutor             *
*           This will quiz you on your Math skills.         *
************************************************************
Intersting Math Facts:
     *The sum of opposite on a standard die is always 7!
     *1000 is the only number from 0 to 1000 that has an a in it!
     *1,089 X 9 = 9,801
     *111,111,111 X 111,111,111 = 12,345,678,987,654,321
************************************************************


Enter your name:Kayley

Hello Kayley, welcome to Math Tutor!
[Level #1]Kayley what is 4 * 2?
8

Congrats! You are correct!
Thank you for playing the game!
Do you want to continue (y=yes | n=no)?y

[Level #1]Kayley what is 5 - 4?
1

Congrats! You are correct!
Thank you for playing the game!
Do you want to continue (y=yes | n=no)?y

[Level #1]Kayley what is 8 - 6?
2

Congrats! You are correct!
Thank you for playing the game!
Congrats! You have upgraded to Level: 2
The numbers are now between 1 and 20
Do you want to continue (y=yes | n=no)?n

===================================
          Summary Report
===================================
Level      Question      Attempts
----- ------------------ ---------
   1    4 * 2  =    8        1
   1    5 - 4  =    1        1
   1    8 - 6  =    2        1

Total Questions:    3
Total Correct:      3
Total Incorrect:    0
Average:          100%

Good work, Kayley!Do you want to continue (y=yes | n=no)?y

Saving game, please wait...
0 questions were successfully saved to the file.
Do you want to continue (y=yes | n=no)?y

Loading game, please wait...
0 questions were successfully saved to the file.

Process finished with exit code -1073741795 (0xC000001D)

```
[To Table of Contents](#table-of-contents)

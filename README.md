# DAXterity
DAXterity is a repository dedicated to practicing and mastering DAX, the formula language used in Power BI for data modeling and calculations. This repository aims to provide a structured environment for learning and experimenting with commonly used DAX functions and patterns.  

> _**80/20 rule, also known as the Pareto Principle, often applies to DAX functions in Power BI. It suggests that 80% of your results can be achieved with just 20% of the functions.**_  

### Frequently Used DAX Functions  
This document provides a categorized list of commonly used DAX functions in Power BI. Use this as a quick reference to improve your data analysis and reporting capabilities.

| Filter                                     | Maths & Stats                 | Date & Time                                 | Text                            | Logical                | Window               |
|:------------------------------------------:|:-----------------------------:|:-------------------------------------------:|:-------------------------------:|:----------------------:|:--------------------:|
| CALCULATE                                  | SUM / SUMX                    | DATEDIFF                                    | CONCATENATE                     | IF                     | WINDOW               |
| FILTER                                     | AVERAGE / AVERAGEX            | DATEADD / SAMEPERIODLASTYEAR                | SEARCH / FIND                   | IFERROR                | INDEX                |
| ALL / ALLEXCEPT / ALLSELECTED              | MAX / MAXX                    | TODAY / NOW                                 | FORMAT                          | COALESCE               | OFFSET               |
| REMOVEFILTER                               | MIN / MINX                    | TOTALYTD / TOTALQTD / TOTALMTD              | UNICHAR                         | OR                     |                      |
| RELATED / RELATEDTABLE / LOOKUPVALUE       | DIVIDE                        | DATESYTD / DATESQTD / DATESMTD              | LEFT / MID / RIGHT              | AND                    |                      |
| DISTINCT / VALUES                          | COUNT / COUNTA                | DATESINPERIOD                               | REPLACE / SUBSTITUTE            | NOT                    |                      |
| EARLIER / EARLIEST                         | COUNTROWS / DISTINCTCOUNT     | DATESBETWEEN                                | UPPER / LOWER / PROPER          | SWITCH                 |                      |
| HASONEVALUE / HASONEFILTER / ISFILTERED    | COUNTX                        | YEAR / MONTH / DAY                          | LEN                             | TRUE                   |                      |
| SELECTEDVALUE                              | RANKX                         | PARALLELPERIOD                              | TRIM                            | FALSE                  |                      |
| USERELATIONSHIP                            |                               |                                             | REPT                            |                        |                      |
| SUMMARIZE                                  |                               |                                             |                                 |                        |                      |

### Logical:
- IF(<logical_test>, <value_if_true>, [<value_if_false>])
- IFERROR (<_value>, <Value_If_Error> )
- COALESCE(<_expression>, <_expression>…)
- OR(logical1, logical2)
- AND(logical1, logical2)
- NOT(<_logical>)
- SWITCH(<_expression>, <_value>, <_result>[, <_value>, <_result>]…[, <_else>])
- TRUE()
- FALSE()

### Text:



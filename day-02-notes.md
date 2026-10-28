Dataset: Global Superstore (51,192 rows) 
Tool: Google Sheets
10 Formulas I Built:
|#|What it finds|Formula|What it does|
| 1 | Total sales | `=SUM(data!R:R)` | Adds up every number in the Sales column. |
| 2 | Total profit | `=SUM(data!N:N)` | Adds up every number in the Profit column. |
| 3 | Average sales per row | `=AVERAGE(data!R:R)` | Adds all sales and divides by how many rows there are. |
| 4 | Average discount | `=AVERAGE(data!F:F)` | Finds the typical discount given on an order. |
| 5 | Largest sale | `=MAX(data!R:R)` | Finds the biggest number in the Sales column. |
| 6 | Smallest sale | `=MIN(data!R:R)` | Finds the smallest number in the Sales column. |
| 7 | Number of order rows | `=COUNT(data!R:R)` | Counts how many numbers are in the Sales column. |
| 8 | Number of loss rows | `=COUNTIF(data!AB:AB,"Loss")` | Counts the rows where Profit Status says Loss. |
| 9 | Highest profit | `=MAX(data!N:N)` | Finds the biggest profit on a single row. |
| 10 | Lowest profit | `=MIN(data!N:N)` | Finds the biggest loss, which is the most negative profit. |
My results: total sales: $12,642,905.00 , total profit: $1,467,457.29 , average sales: $246.50 , average discount: 14.29%, largest sale: $22,638.00 , smallest sale: $0.00 , rows: 51,192, loss rows: 710 , highest profit: $8,399.98 , lowest profit: -$6,599.98 .
 **IF:** `=IF(N2>0,"Profit","Loss")` checks whether profit is above zero. It shows "Profit" if yes and "Loss" if no. I used it to label every row.
 **COUNTIF:** `=COUNTIF(A:A,"Technology")` counts how many rows contain the word Technology in the Category column.
Observations:
Technology has 10,141 rows out of 51,192, about 19.8% of the dataset.
Technology products include keyboard, memory card, and USB.

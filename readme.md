Module 2 Challenge

In the context of analyzing stock market data using VBA scripts, a ticker symbol is a unique identifier for a particular stock. Each row in your data set corresponds to a specific date and stock, and you need to extract and analyze information such as the ticker symbol, opening price, closing price, and stock volume from each row.

These are the steps I followed:

1. Use a loop to loop through each row of the data set.
2. Extracted the ticker symbol: For each row, I extracted the ticker symbol.
3. Extracted data: Extracted other relevant data such as opening price, closing price and stock volume for that particular row.
4. Perform calculations:
· Calculate the annual change from the opening price to the closing price.
· Calculate the percentage change.
· Track total share volume for each ticker symbol.
5. Generate the calculated values (ticker symbol, annual change, percentage change, total stock volume) for each row.
6. Conditional formatting: Apply conditional formatting to highlight positive changes in green and negative changes in red.
7. Additional tasks: Implement functionality to find the stocks with the largest percentage increase, the largest percentage decrease, and the highest total volume.
8. The script can run successfully on all sheets (representing different years).
9. GitHub Repository: Create a new repository, add VBA files and submit the task on GitHub.
# Console Finances

## Overview

In this project, I analyzed a financial dataset using JavaScript.
My goal was to calculate various financial metrics to gain insights into the company's performance.

## Instructions

**Analyzing Financial Records:**
- Write JavaScript code to calculate the following financial metrics:
- Total number of months in the dataset.
- Net total amount of Profit/Losses over the entire period.
- Average change in Profit/Losses over the entire period.
- Greatest increase in Profit/Losses (date and amount).
- Greatest decrease in Profit/Losses (date and amount).

**Console Output:**
- When you run your code, the resulting analysis should be printed to the console.
- Example output:
   Financial Analysis 
   ----------------
   Total Months: 86
   Total: $38382578
   ```text
   Average Change: -2315.12
   Greatest Increase in Profits/Losses: Feb-2012 ($1926159)
   Greatest Decrease in Profits/Losses: Sep-2013 ($-2196167)
   ```
## General approach

I initially attempted to create an empty array to store all the changes, pushing each change into this array. I then utilized Math.max and Math.min to identify the largest increase and decrease, respectively. However, I soon realized that this method did not capture the associated months. To address this, I modified my logic by incorporating if statements to track and save the corresponding months during the analysis.

## Lessons learned

I successfully completed the "Console Finances" challenge. Through this project, I was able to practice my JavaScript skills into a real-world financial dataset.
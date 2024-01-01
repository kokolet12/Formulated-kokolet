# Introduction
![kpi intro pge](https://github.com/kokolet12/Formulated-kokolet/assets/155350323/9be9a181-e72a-43f0-ad12-e0a1f9926e76)
This data was downloaded for the sake of data cleaning and visualization. I look up to the challenges I will get from this file for I have been trying to practice my skills.
#### Problem Statement
-	How to know the KPI’s of the firm 
-	How to know the average age, BMI, temperature, blood pressure, cholesterol, heart rate, weight and height, the count of various blood group, the count of smokers and the count of diabetic patients using pivot table and charts with indications.
#### Data sourcing
Not until after stating these questions, before I went ahead to search for a file that suits it. The file contains two sheets.
#### Data manipulation
*The following KPI’s were gotten with these formulas to get a better understanding of this project.*
-	Total Revenue =SUM(A2:A701), Total Profit , Average Profit =AVERAGE(L2:L701), Lowest Profit =MIN(L2:L701), Highest Profit =MAX(L2:L701), Number of Transactions =COUNT(L2:L701) and Profit Margin =W2/W1.
-	Total unit sold , Total unit sold in Mexico =SUMIF(C2:C701,"mexico",O2:O701), Total profit in Canada, average profit made in Canada for paseo =AVERAGEIFS(L2:L701,C2:C701,"Canada",K2:K701,"Paseo"), total profit made in Canada for paseo in 2014 =SUMIFS(L2:L701,C2:C701,"Canada",K2:K701,"Paseo",P2:P701,"2014"), number of sales recorded in July =COUNTIF(I2:I701,"July"), Average unit of goods sold (Paseo, Canada, 2014) =AVERAGEIFS(O2:O701,C2:C701,"Canada",K2:K701,"Paseo",P2:P701,"2014"), The average revenue generated from each sale of Paseo =AVERAGEIF(K2:K701,"Paseo",A2:A701), The number of sales made in the government segment =COUNTIF(N2:N701,"Government"), the number of sales made in the midmarket segment, The total revenue generated from the sales of Montana in Canada =SUMIFS(A2:A701,K2:K701,"montana",C2:C701,"canada"), Highest unit of goods sold (year) =VLOOKUP(W29,O2:P701,2,FALSE) Vlookup always look backward and not forward, Highest unit of goods sold (Month), Highest unit of goods sold (segment), Highest unit of goods sold (Country), Total profit made in December and Highest unit of goods sold
-	The average and count pivoted table were fixed from following the basic steps: Click on inset tab, click pivot table, click from table/range and choose a new sheet.
-	The average and count pivoted chart were fixed from following the basic steps: click on the already existing pivot table then click pivot table analysis and choose chart then choose clustered column to visualize the table. 
#### Recommendation
As far as data cleaning is important, data visualization is also important for clarity’s sake. With KPI’s the shareholders would be able to know what year had the highest or lowest sales, the total amount spent on manufacturing the product and its profit.
#### Conclusion
KPI’s and data visualization helps shareholder to make meaningful decisions that would help the company to move forward.

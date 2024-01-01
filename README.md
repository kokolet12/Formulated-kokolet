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
![KPI1](https://github.com/kokolet12/Formulated-kokolet/assets/155350323/a8983e04-9d41-4c77-9c63-46df9cf6ea0a)
-	Total unit sold , Total unit sold in Mexico =SUMIF(C2:C701,"mexico",O2:O701), Total profit in Canada, average profit made in Canada for paseo =AVERAGEIFS(L2:L701,C2:C701,"Canada",K2:K701,"Paseo"), total profit made in Canada for paseo in 2014 =SUMIFS(L2:L701,C2:C701,"Canada",K2:K701,"Paseo",P2:P701,"2014"), number of sales recorded in July =COUNTIF(I2:I701,"July"), Average unit of goods sold (Paseo, Canada, 2014) =AVERAGEIFS(O2:O701,C2:C701,"Canada",K2:K701,"Paseo",P2:P701,"2014"), The average revenue generated from each sale of Paseo =AVERAGEIF(K2:K701,"Paseo",A2:A701), The number of sales made in the government segment =COUNTIF(N2:N701,"Government"), the number of sales made in the midmarket segment, The total revenue generated from the sales of Montana in Canada =SUMIFS(A2:A701,K2:K701,"montana",C2:C701,"canada"), Highest unit of goods sold (year) =VLOOKUP(W29,O2:P701,2,FALSE) Vlookup always look backward and not forward, Highest unit of goods sold (Month), Highest unit of goods sold (segment), Highest unit of goods sold (Country), Total profit made in December and Highest unit of goods sold
  
![KPI2](https://github.com/kokolet12/Formulated-kokolet/assets/155350323/142c44a0-f5be-4cb5-9666-910d64e821d5)

![KPI3](https://github.com/kokolet12/Formulated-kokolet/assets/155350323/ad2ca604-a45c-4e3f-b425-53d789df0a2b)

-	The average and count pivoted table and charts were inserted.
![PTC AVG age](https://github.com/kokolet12/Formulated-kokolet/assets/155350323/c5445f2a-f811-496b-be1f-f2b088289143)

![PTC AVG BMI](https://github.com/kokolet12/Formulated-kokolet/assets/155350323/13897509-02f4-45a5-ac8f-4af33f0b265a)

![PTC AVG bld pr](https://github.com/kokolet12/Formulated-kokolet/assets/155350323/7f017195-9c3a-42ce-ac34-33d104d62f8a)

![PTC AVG hrt rt](https://github.com/kokolet12/Formulated-kokolet/assets/155350323/f19597ac-9396-411e-a035-ee1d92ef89f1)

![PTC AVG temp](https://github.com/kokolet12/Formulated-kokolet/assets/155350323/d451f27a-aac4-4f15-af95-ec08b6328390)

![AVG choles](https://github.com/kokolet12/Formulated-kokolet/assets/155350323/44a01260-5295-4dc3-972f-cae7b9b0c3e2)

![AVG wei, Hei](https://github.com/kokolet12/Formulated-kokolet/assets/155350323/bc62e733-5725-4989-88d7-e25f16a7c94f)	

-	The count pivoted chart were fixed from following the basic steps: click on the already existing pivot table then click pivot table analysis and choose chart then choose clustered column to visualize the table.
![COUNT bld grp](https://github.com/kokolet12/Formulated-kokolet/assets/155350323/1e76b862-eec4-4d4e-9cbd-3b2dfe0381a6)

![COUNT smk](https://github.com/kokolet12/Formulated-kokolet/assets/155350323/22238016-1d79-4a6d-a856-5167013d90b5)

#### Recommendation
As far as data cleaning is important, data visualization is also important for clarity’s sake. With KPI’s the shareholders would be able to know what year had the highest or lowest sales, the total amount spent on manufacturing the product and its profit.
#### Conclusion
KPI’s and data visualization helps shareholder to make meaningful decisions that would help the company to move forward.

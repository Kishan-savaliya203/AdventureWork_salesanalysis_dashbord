# AdventureWork_salesanalysis_dashbord
𝑷𝒓𝒐𝒋𝒆𝒄𝒕 𝒐𝒗𝒆𝒓𝒗𝒊𝒆𝒘:

➡️I had the opportunity to complete a project with Adventure Works Data set. Adventure Works is a bike manufacturer and seller and in this project I analyze their sales and returns data using Microsoft 
   Power BI Desktop.This was an end to end project beginning with importing and data cleaning and ending with the creation of visuals and optimization of those visuals.


𝑫𝒂𝒕𝒂 𝒔𝒐𝒖𝒓𝒄𝒆𝒔:

➡️The raw data set given in .csv format by ADVENTUREWORKS and was imported to Power BI directly. A total of 8 files were imported, each being their own table.


𝑻𝒐𝒐𝒍 𝒖𝒔𝒆𝒅:

➡️Microsoft power bi


𝑫𝒂𝒕𝒂 𝒑𝒓𝒆𝒑𝒂𝒓𝒂𝒕𝒊𝒐𝒏:

➡️𝘿𝒂𝙩𝒂 𝒄𝙡𝒆𝙖𝒏𝙞𝒏𝙜: from row data I was able to get a general overview of the data set and saw that I would primarily be working with Sales and Returns data then began cleaning the data by ensuring columns 
                  were titled appropriately, they were in their correct data types, looking for missing data (which there was none) and began looking for what relationships I might be able to create 
                  between these tables.




➡️𝑫𝒂𝒕𝒂 𝒎𝒐𝒅𝒆𝒍𝒊𝒏𝒈: After ensuring my data’s accuracy and consistency, began the process of creating a data model for my tables. first established my data tables which are ‘Sales Data’ and ‘Returns Data’ 
                   then set work creating relationships between tables. For this project I did not find it necessary to use any relationships other than one to many. A picture of the completed model is 
                   provided for greater understandig.


![Screenshot 2024-05-24 010817](https://github.com/Kishan-savaliya203/AdventureWork_salesanalysis_dashbord/assets/167234170/a94d40e2-4e96-472b-9603-9525f9952150)




➡️𝑫𝑨𝑿 𝑭𝒖𝒏𝒄𝒕𝒊𝒐𝒏𝒔:Now that I had established my table relationships, I could begin utilizing some DAX functions to analyze the data set. I started by creating basic KPI’s such as Revenue, Profit, and 
                  Total Orders which would help me to calculate more advanced metrics later on. Some of the DAX functions I used the most include:

                  ITERATOR FUNCTIONS (SUMX): These are formulas which evaluate an expression based on each row and then aggregate the results.
                  CALCULATE(): acts as an overriding filter to give you a new filter context. Was incredibly useful for establishing Previous Months Orders, Revenue, Profit, Returns and Overall Average 
                               Price
                  RELATED(): This function allows you to pull data from different tables as long as there is an established many to one relationship.
                  Date Functions(DateAdd, DATESINPERIOD): These date functions were very helpful when establishing a 90 Day Rolling Profit as well as the Previous Months Order, Profit, Revenue and Returns.






                   



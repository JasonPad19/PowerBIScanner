# Please Star PowerBI Scanner if you like it.



# PowerBI Scanner
Build a power bi report to understand and monitor the artefact in your report.
- How many data sources we have? 
- is it web content(URL) , sql database (Server, Database, Table/View), DocumentDB (URL, Collection, Entity)
- How many datasets have been used in a report?
- What are the power query scripts?
- Do we have DAX measure? what are the DAX scripts?





# Methodology 
PowerBI is using DataModelSchema to store the metadata, thus, we could read and report the metadata
- Measures can be found in: model.tables.measures
- Columns can be found in: model.tables.columns
- Calculated Columns can be found in: model.tables.columns 


# Compatibility
Compatible with May 2021 Power BI Desktop


# Demo 

If you want a similar report as below or further changes, please email to JasonJiangBiz@gmail.com.


![image](https://user-images.githubusercontent.com/52347372/123221078-a93ec680-d522-11eb-99c5-7bab4b2f4f0a.png)

![image](https://user-images.githubusercontent.com/52347372/123350583-670f9680-d5af-11eb-8e62-c4d9ef6ebb08.png)

![image](https://user-images.githubusercontent.com/52347372/123350552-58c17a80-d5af-11eb-8900-f158f8458e8a.png)

![image](https://user-images.githubusercontent.com/52347372/123221127-b78ce280-d522-11eb-9a91-41c7af9ea708.png)


![image](https://user-images.githubusercontent.com/52347372/123221145-c07db400-d522-11eb-9e3c-0e2ccd50178e.png)


Here is a sample report for your reference.

https://app.powerbi.com/view?r=eyJrIjoiNjI3NDFhM2EtZDQ0MS00Y2FiLWE1ZTItYzY5OThmNjhmMjY5IiwidCI6IjcxY2ZiZjg4LTE2ZWItNGVjMC05M2E2LTYzYzNkMWRlMWY0MyJ9





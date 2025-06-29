# Food-Price-Analysis-in-Bangladesh
## Introduction:
The information used in this analysis are derived from the World Food Programme (WFP), comprising food price information collected in various divisions in Bangladesh for a few years (1998–2024). It includes significant variables such as type of commodity, market location, administrative region, types of prices (wholesale/retail), and pattern of time. This work attempts to analyze long-term trends in prices of staple food items like rice, wheat, lentils, and oil, helping to identify market imbalances, regional gaps, and suggest regulatory areas of focus. Bangladesh being susceptible to climatic shocks, economic upheavals, and global events like the COVID-19 pandemic, this work serves as a decision-support tool for government agencies, NGOs, and policy makers.
## Data Cleaning and Preparation:
The raw dataset required some preprocessing procedures to render it analytically clean. Certain initial problems were:
•	Column header Issues: There were two columns as heading. In power query, the most meaningful one is kept as header, where another one was removed.
•	Data type: Few columns were not identified as proper data type. For example, Date was not as a date format, instead it was in text format. Also the columns where we have price was also changed into decimal type of data from text data.
•	Categorical Consistency: It was found different types of rice category added. Those all categories were replaced as single “Rice” type category so that we have less legend to form graph and also to do better comparison among categories.
•	Currency Discrepancies: Though the dataset had prices in local currency as well as USD, the analysis was performed for local currency to symbolize domestic market trends.

# ASO
* Azure Start Offer Hands on Lab

# Agenda  
* Day 1  
10:00 - Greetings and Opening(Scenario 설명)   
10:20 - Hands on Lab (Configure Azure Services)   
11:30 - Lunch   
13:00 - Hands on Lab (Orchestrate with Azure Data Factory 1)   
14:00 - Break Time   
14:15 - Hands on Lab (Orchestrate with Azure Data Factory 2 & Visualize data with Power BI Desktop)   
15:15 - Break Time   
15:30 - Hands on Lab (Machine Learning)   
17:00 - Closing  

# Solution Architecture
![SolutionArchitecture](https://github.com/azure-datasolution/ASO/blob/master/SolutionArchitecture.png)

# References
* CloudScaleAnalytics 
https://github.com/azure-datasolution/CloudScaleAnalytics  

# ETC
* Email URL
https://prod-06.koreacentral.logic.azure.com:443/workflows/21f3052675d24be0aa4298a9b0490ce8/triggers/manual/paths/invoke?api-version=2016-10-01&sp=%2Ftriggers%2Fmanual%2Frun&sv=1.0&sig=BfXuXTp05p20wnvDFzkUgi3xbf3XGSB-1qapyC_EDFA

{"DataFactoryName":"@{pipeline().DataFactory}","PipelineName":"@{pipeline().Pipeline}",
"Subject":"Pipeline Succeeded","Message":"Succeeded!","EmailTo":"본인의 메일계정"}

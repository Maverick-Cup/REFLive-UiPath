# REFLive-UiPath

Description - Project take input from excel file, then checks the country on Google and writes back the result to Excel file. 

Refer - Skip REFDemo1 as it was shown for understanding the flow. 
REFLive folder as main, it has implementation of RE Framework which acts as performer of these activities and read the Country from Queue which is saved in cloud.uipath.com. Data file path is saved in the same url in Asset (which is a placeholder for the property such as ExcelPath file). 
Then - Dispatcher project read the Data file using Path saved in Asset and then writes it in Queue saved in cloud.uipath.com.

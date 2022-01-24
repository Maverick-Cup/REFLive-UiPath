# REFLive-UiPath

Descp - Project take input from excel file, then checks the country on Google and wrties back the result to Excel file.
Refer - Skip REFDemo1 as it was shown for understanding the flow.
REFLive Folder as main, it has implementation of RE Framework.which acts as performer of these activites and read the Country from Queue which is saved in cloud.uipath.com. Data file path is saved in the same url in Assest (which is a placeholder for the property such as ExcelPath file).
Then - Dispatcher project read the Data file using Path saved in Assest and then writes it in Queue saved in cloud.uipath.com.

# FDB_AWR_Analyzer
AWR Analyzer


Hi,

 Here i have a excel tool for do analysis on AWR Repository, I have developed it with VBA language (Visual Basic for Applications). This tool is capable for create normal and pivot charts (bar, lineal, area, etc.) for every metric (topquery, event waits, sysmetric, systat, etc.) for every Rac Instance. For instance, with this tool you can show charts about the top querys, top event waits, top sys time model, sysmetrichistory, database growth, etc. for any date you want. And the connectivity to database is so easy, I use the same Oracle Client for do connectivity.

For instance, the first page is called "Inicio" in this page you should to enter the ip address, port, service_name, username and password for database.



And after that you can go for example to page is called "TopQuerys" and the only thing you should to do is click en the button "Actualizar Grafico" for generate the top querys chart.



This is the output (you can see information for different metrics: buffer gets, physical reads, cpu used, elapsed time, etc..):



As can you see that it was a pivot chart very powerfull, you can select and filter for specific sqlid list too. And if you want you can add filter to query for example change the dates for snaps:



Also you can select for the last chart for navigate for specific sqlid:


And you can see information only for that sqlid for that snap :)   (module, machine, cpu used, physical read, exadata statistics, parsing, etc..):


That information is the same for all sheets for the worksheet, so in this way you can review systimemodel, sysstat, topquerys, topobjects I/O, and more.

Also you have a dashboard sheet (the sheet's name is "Dashboard") with the last information  about the last minute for performance database for every Rac Instance:



I hope the worksheet it would be great helpfull for your performance analysis. Please don't change the code or change my copyright.

This is the link for download the tools. Please tell me if you have problem about it:
https://drive.google.com/file/d/1_XarxTcizAJTXc8txS_bYWCeEL5CPCcV/view?usp=sharing

I will hope your comments by means my email: felipe.donoso@oracle.com or felipe@felipedonoso.cl
Byee
Atte. Felipe.

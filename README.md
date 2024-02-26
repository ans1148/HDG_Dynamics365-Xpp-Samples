# HDG-Dynamics365-X++-Samples
Code sample collection of D365 ERP written in X++.
Written by Dong-Gyun Ha.

# Execute direct SQL from Dynamics365 ERP form

In order to overcome the limitation of not being able to create and execute a direct query in the cloud version, it is a function that allows you to create a query yourself on the form.

Refer : [XppTools Git](https://github.com/TrudAX/XppTools/tree/master/DEVTools/DEVSQLExecute)   
I have refactored the code in the above reference link. Also, I add the some functions that if update mode is selected then enabling only screen output.

![Execute direct SQL](img/ExecuteDirectQuerySample.png)

# Send an email to the SSRS report as an attachment

Please refer "Report_Send_Email" folder.

![Send Email as attachment](img/ReportSendEmailSample.png)

# Send an email

Please refer "Send_Email" folder.

Document : [Microsoft document](https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/dev-tools/sysmailer-develop?context=%2Fdynamics365%2Fcontext%2Fcommerce#sending-emails) 

![Send Email](img/SendEmailSample.png)
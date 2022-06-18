# webzaloapioa
https://localhost:44353/webzaloapioa.csproj 
#HTTP Error 404.7 - Not Found
The request filtering module is configured to deny the file extension.

#Most likely causes:
Request filtering is configured for the Web server and the file extension for this request is explicitly denied.


#Things you can try:
Verify the configuration/system.webServer/security/requestFiltering/fileExtensions settings in applicationhost.config and web.config.

#Detailed Error Information:
Module	   RequestFilteringModule
Notification	   BeginRequest
Handler	   aspNetCore
Error Code	   0x00000000
Requested URL	   https://localhost:44353/webzaloapioa.csproj
Physical Path	   C:\Users\nd_ch\Downloads\webzaloapioa\webzaloapioa\webzaloapioa.csproj
Logon Method	   Not yet determined
Logon User	   Not yet determined

# webzaloapioa

#HTTP Error 404.7 - Not Found
The request filtering module is configured to deny the file extension.

#Most likely causes:
Request filtering is configured for the Web server and the file extension for this request is explicitly denied.


#Things you can try:
Verify the configuration/system.webServer/security/requestFiltering/fileExtensions settings in applicationhost.config and web.config.


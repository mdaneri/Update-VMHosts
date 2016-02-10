# Update-VMHosts
This cmdlet updates the specified hosts. The cmdlet installs patches on the host. 
The patches that can be located locally or on a Web location.
When using the LocalPath or WebPath parameters, the ESX/ESXi host attempts to store the patch contents in its local temporary directory.
If you want you can install patches packaged in a ZIP archive,without the need to extract them; specify the zip file in LocalPath parameters.
If you use the LocalPath parameter as directory, you must extract each patch to a folder. The name of the folder must contain the patch ID (for example,"ESXi600-201601001").  
If you use the WebPath parameter, you must extract each patch to a folder that is published on a Web server. 
The patch URL address must contain the patch ID (for example, http://myInternalWebServer/ESXi600-201601001 ). 
Depending on the component to be upgraded, you might have  to restart the host or the hostd management service after applying the patch.

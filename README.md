1.	Storage Account creation and Security Implementation

2.	The project demonstrates the storage account created and public network access disabled, accessed using a private endpoint. SAS URL created for blob container document access.

3.	Architecture

4.	VM (deployed inside specific VNet)  ---private endpoint-- storage account ---- SAS URL 

5.	Deployment steps:
6.	Created resource group
7.	Deployed Virtual network and VM
8.	Created a storage account.
9.	Public network access is disabled on the storage account firewall settings
10.	Private endpoint created 
11.	Private endpoint checked inside VM using the nslookup command.
12.	RBAC permissions assigned storage Blob data contributor and storage Blob Data reader.
13.	SAS URL generated and accessed uploaded Test.docx inside the storage container.
14.	SAS URL expiry time set up.



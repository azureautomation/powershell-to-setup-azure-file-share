PowerShell to Setup Azure File Share
====================================

            

Azure File Share is an awesome feature of Azure for sharing your files with all your computers. Today we take a look at creating Azure File Share using PowerShell.


In this article, I would walk you through on how to implement Azure File Share using PowerShell.


Let’s begin.


**Step 1**: Login to Azure account using the command


 

 

![Image](https://github.com/azureautomation/powershell-to-setup-azure-file-share/raw/master/1.png)


 


**Step 3**: For creating a new Storage Account in a Resource Group, use the below command.


 

 

![Image](https://github.com/azureautomation/powershell-to-setup-azure-file-share/raw/master/1.png)


 


Now the below command would store one of the Storage Key value in a variable (in this case $key1 is the variable name).


 

![Image](https://github.com/azureautomation/powershell-to-setup-azure-file-share/raw/master/1.png)

 


Using the Access Key and Storage Account name you can now create the Storage Context using below command.


 

 

![Image](https://github.com/azureautomation/powershell-to-setup-azure-file-share/raw/master/1.png)


 


**Step 5**: With the Storage Context created, you can now proceed with the creation of Azure File Share using the given command.


 

 

![Image](https://github.com/azureautomation/powershell-to-setup-azure-file-share/raw/master/1.png)


 


![Image](https://github.com/azureautomation/powershell-to-setup-azure-file-share/raw/master/1.png)


*Pat Your Back*, as now you have your Azure File Share ready.


**Step 6**: In order to have your data uploaded to the File Share, use the following command to create a Directory.


 

 

![Image](https://github.com/azureautomation/powershell-to-setup-azure-file-share/raw/master/1.png)


 


 

![Image](https://github.com/azureautomation/powershell-to-setup-azure-file-share/raw/master/1.png)

 


To upload files to the created Directory, you can type-in below command.


 

 

![Image](https://github.com/azureautomation/powershell-to-setup-azure-file-share/raw/master/1.png)


 


 

![Image](https://github.com/azureautomation/powershell-to-setup-azure-file-share/raw/master/1.png)


 


To have a visual satisfaction, you can verify the Azure File Share details on the Portal as shown below.


![Image](https://github.com/azureautomation/powershell-to-setup-azure-file-share/raw/master/1.png)


 



 


Hope this article will be helpful.


Thank You!!


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.

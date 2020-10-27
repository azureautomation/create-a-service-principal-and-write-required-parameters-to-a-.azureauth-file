Create a Service Principal and write required parameters to a .azureauth file
=============================================================================

            

**New-ServicePrincipalAsReader** is a PowerShell script to create a Read only Service Principal in Azure.


The script will write a file ([subscriptionName].azureauth) with all the parameters needed to use the Microsoft.Azure.Management.Fluent lib.
SECURITY: The file [subscriptionName].azureauth will contain the key for the Service Principal.

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.

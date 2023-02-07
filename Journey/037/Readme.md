Creating a Powershell Script 

Today we are doing a project :)

  

☁️☁️☁️ Requirments for our powershell script 

  1- Create multiple VMs (this script will need to be in a loop)
  2- Create three VMs in 3 different Resource Groups (RG name will have to be a parameter)


☁️☁️☁️ Background Information for Scripts/ Scripting

☁️Script extentions 

  This is the ending of the name of the script, which indicates which scrpiting language is in the script. 
  
  powershell the extenstion is .ps1
  
  Bash the extention is .sh 


☁️Comments

  Comments are important to allow easy understanding of the script. Comments are marked with a "#" at the beginning of the line
  
  Nothing after the "#" is read in the script / executed, it is just there for human reading
  
  
  
Activity location : https://learn.microsoft.com/en-us/training/modules/automate-azure-tasks-with-powershell/8-exercise-create-resource-using-script 


The script we completed and successfully tested was as follows 

    param([string]$resourceGroup)
    $adminCredential = Get-Credential -Message "Enter a username and password for the VM administrator."
    For ($i = 1; $i -le 3; $i++)
    {
    $vmName = "ConferenceDemo" + $i
    Write-Host "Creating VM: " $vmName
    New-AzVm -ResourceGroupName $resourceGroup -Name $vmName -Credential $adminCredential -Image Canonical:0001-com-ubuntu-server-focal:20_04-lts:latest
    }

    

[link](link)

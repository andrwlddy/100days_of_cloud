Adding users to Azure Active Directory 


https://learn.microsoft.com/en-us/training/modules/create-users-and-groups-in-azure-active-directory/2-user-accounts-azure-ad 


https://learn.microsoft.com/en-us/training/modules/create-users-and-groups-in-azure-active-directory/3-exercise-add-delete-users-azure-ad 


BULK CREATE USERS 

$invitations = import-csv c:\bulkinvite\invitations.csv

$messageInfo = New-Object Microsoft.Open.MSGraph.Model.InvitedUserMessageInfo

$messageInfo.customizedMessageBody = "Hello. You are invited to the Contoso organization."

foreach ($email in $invitations)
   {New-AzureADMSInvitation `
      -InvitedUserEmailAddress $email.InvitedUserEmailAddress `
      -InvitedUserDisplayName $email.Name `
      -InviteRedirectUrl https://myapps.microsoft.com `
      -InvitedUserMessageInfo $messageInfo `
      -SendInvitationMessage $true
   }
   
   
   
   
   
   
## ☁️ Cloud Outcome

✍️ (Result) Describe your personal outcome, and lessons learned.

## Next Steps

✍️ Describe what you think you think you want to do next.

## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[linkedin post](https://www.linkedin.com/posts/andrew-leddy_100daysofcloud-azure-activity-7043057306443407360-Q8Wy?utm_source=share&utm_medium=member_desktop)

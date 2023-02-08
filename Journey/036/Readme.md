Exercise - Create an Azure Resource using scripts in Azure PowerShell

![create vm](https://user-images.githubusercontent.com/102994059/217330773-cff9f340-c519-4d8b-a704-c4d746ad9845.jpg)


☁️ New-AzVm .......... as seen above this is the command used to create a new VM in Azure Cloud SHell

    $vm = (Get-AzVM -Name "testvm-eus-01" -ResourceGroupName learn-3231985b-0f43-4fe3-b6ec-5c557e5463c1)
    
 The above command containes extra options to all specific details about the new VM

![newvm](https://user-images.githubusercontent.com/102994059/217331643-682142e1-239b-43a3-b417-58542ef7ff76.jpg)

above is what it looks like once  you have successfully created a new vm!!!!


☁️☁️☁️ Get public IP Addr


    Get-AzPublicIpAddress -ResourceGroupName learn-3231985b-0f43-4fe3-b6ec-5c557e5463c1 -Name "testvm-01"
    


## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](https://www.linkedin.com/posts/andrew-leddy_100daysofcloud-azure-activity-7028904235786235904-LZhb?utm_source=share&utm_medium=member_desktop)

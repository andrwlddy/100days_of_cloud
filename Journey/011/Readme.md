CREATING AN AZURE RESOURCE LOCK 

![arl](https://user-images.githubusercontent.com/102994059/200705213-924c5a10-243e-4fe5-92b6-85235ab59ed7.png)


## Introduction
☁️ WHAT IS A RESOURCE LOCK?

  Azure allows you to create "Resource Locks" on resources. This is a way to protect the resource from user acitivty you DONT want to occur. For example, if you want a resource to not be able to be delted, you can create a lock and apply it to that resource. 


## Cloud Research

☁️☁️☁️ CREATING A RESOURCE LOCK


### Step 1 — creating a resource group
![screenshot1](https://user-images.githubusercontent.com/102994059/200705994-62968630-c797-4660-a646-7a57da6a5657.jpg)

Above is a quick image from us creatinga our resource group. Resource groups we have already gone over in this challenge. Since we will be applying this lock to a resource group, creating a resource group is of course step 1. 

### Step 2 — Creating the resource lock 

![screenshot2](https://user-images.githubusercontent.com/102994059/200706467-fbe2c536-c42e-4c27-860d-4874aa5a37fb.jpg)

Highlighted you can see the Locks section. From there, we click "add" (also highlighted). We then are given two options....

Read Only and Delete. These are the two different types of locks in Azure. 

The difference between these two is actually not quite as simple as you might think, as the specific resource this lock is attached to impacts what it does. For further information on these, look at the azure documentation here : https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources?tabs=json 




## ☁️ Cloud Outcome

Today we learned what an Azure resource lock was, and we step  by step learned how to create one. 


## Social Proof

 Show that you shared your process on Twitter or LinkedIn

[linkedin post](https://www.linkedin.com/feed/update/urn:li:share:6995907261663485952/)

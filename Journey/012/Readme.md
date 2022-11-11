Exercise: Restrict deployments to a locatin using Azure Policy


![image-29](https://user-images.githubusercontent.com/102994059/201111798-ff0dd8cc-b520-47c7-bb7a-93c3b7822d07.png)


## Introduction

☁️ (Why) Understandig Azure Policy is important for anyone that will be using Azure. This exercise will teach us about Azure Policy, and then how to use it. 



WHAT IS AZURE POLICY?

Much like the name suggest, Azure policy is used to enforce company wide standards/policies. it provides an aggregated view to evaluate the overall state of the environment, with the ability to drill down to the per-resource, per-policy granularity. 



## EXERCISE


### Step 1 — Create a resource group
  
  we did this last exercise.. so we will not show you how to do this. You do need a resrouce group to continue however


### Step 2 — Head over to the Azure Policy page

From the home screen, simply search "policy" and you will be taken to the policy page



### Step 3 — Explore predefined policies 

(https://user-images.githubusercontent.com/102994059/201115737-c410b61b-ec32-4896-9e6e-96dfbcb72e40.jpg)

is this pic above is the policy screen. There is a lot to do here, but to explore policies click "defintions" (highlighted). Predefined policies live here. 


### Step 4 — Create the new policy 

click on "assignments" to create a new policy. An assignment is a policy that has been assigned to take place within a specific scope. Click "Assign Policy" (highlighted below in image)


![policy](https://user-images.githubusercontent.com/102994059/201116669-51b17c0f-3dea-4001-a694-65cb3b243260.jpg)

Assign Policy Final Step

![policy](https://user-images.githubusercontent.com/102994059/201117193-19c865d5-9c95-468e-b474-0c710a982ed0.jpg)

From here, you can specify which policy you want to enforce, and to which scope. Notice the tabs as you will need to enter information into all of these tabs to fully assign the policy. Below is one last screenshot showing how we can specifically allow or deny resource creation by regions! Very cool!!!!

![policy](https://user-images.githubusercontent.com/102994059/201118072-676b0665-1694-4752-b311-83bc6a322d7f.jpg)



## ☁️ Cloud Outcome

☁️ (Result) Today we learned what Azure policy was, what an assignment was, and how to implement a policy in our cloud environment!!!



## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](https://www.linkedin.com/feed/update/urn:li:activity:6996593509587648512/)



VIRTUAL MACHINES

![VMs](https://user-images.githubusercontent.com/102994059/199365893-b16ccf55-da3c-4bd7-bfe5-0fae238c9790.jpg)

## Introduction

☁️ Virtual machines are absolutley pivotal to understand in order to understand cloud computing and how it works. VMs are one of many resources of Azure, and are a IaaS solution. 

☁️☁️☁️WHERE THE VIRTUALIZATION TAKES PLACE 

VMs are often confused with containers, and they are fundamentally different. This difference is very important to understand. Understanding where virtual machines are virtualized helps us fully understand the difference between VMs and other Azure resources and solutions. 

VMs are virtualized at the OS level. Containers are a the app level. 

![vms virt](https://user-images.githubusercontent.com/102994059/199366709-3534f434-52f2-40e7-910d-12766ed168ae.jpg)

referring to the above image, you can see a fundamental characterstic of VMs..... they are stacked on a hypervisor. A hypervisor is a program that is used to manage the VMs. On this hypervisor , each VM has its own OS. This is a key advantage to VMs and wil be further discussed in the next section. 



☁️☁️☁️WHEN ARE VMS USED???

One of the main advantages to VMs is you can have multiple OS on the same peice of physical hardware. This makes VMs great for testing apps. 

Another good reason VMs are great for testing is they provide a safe, sandboxed environment. 

VMs can also support legacy apps.

☁️☁️☁️WEAKNESSES OF VMs

VMs of course have weaknesses too. The main one is unstable performance. Applications typically have resources requriements, and VMs will typically have a hard time keeping up with Applicaitons that have higher requirements. 


☁️☁️☁️CREATING A VM


![create a vm 1](https://user-images.githubusercontent.com/102994059/199368268-f37c9332-ffda-4d13-83bf-f4d3f280c18f.jpg)

Above is the create a resource screen in the azure portal. If you were to create a VM, you would click on the "create" button just below the highlighted text.




Fromt here, you would see the image below. 

![azure how to 2](https://user-images.githubusercontent.com/102994059/199368521-8ceafb12-d567-4711-9c32-7091172a2067.jpg)


This is where all the settings are created, including the azure subscription that will be used and the OS of the VM. Some of these setting are extremeley important so a thorough understanding of all these setting is needed to successfully deploy a VM.

For example, one of the settings is Inbound Ports. this is incredibly important to understand as how we eventually connect to this VM will depend on what we select. 


## Social Proof


[linked In post](https://www.linkedin.com/posts/andrew-leddy_100daysofcloud-activity-6993373296658382848-_DJO?utm_source=share&utm_medium=member_desktop)

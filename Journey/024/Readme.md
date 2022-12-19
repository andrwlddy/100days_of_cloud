Sentinel Prerequisites



![sentinel](https://user-images.githubusercontent.com/102994059/208499707-fcbaa15a-26d3-48d0-8ee2-dc123ba0fb4a.png)


What do you need to do before setting up Microsoft Sentinel? 

Thats what this post today will be about. Since I am going for SC-200 certificaiton, Azure Sentinel is something I will have to master in the upcoming weeks. I expect most of my future posts to be related to sentinel in some way. 

Pre Deployment Activities

The pricing of Sentinel is something that is very important to consider. Below is the most up to date pricing models for Sentinel as of today, 12/19/22

![Sentinel Pricing](https://user-images.githubusercontent.com/102994059/208500778-e2871932-dd42-420a-b487-d2fbc0a86ff2.jpg)

As you can see, there is a wide range of options and your direction needs to be determined before you start with sentinel. Like most things in the cloud, extensive planning is a requirement to successfuly implement this new tool. 

The first step is determining data sources and data size requirements to accurately project a budget. 

    Data sources, or data connectors,  enable you to use data connectors to configure connections with different Microsoft services, partner solutions, and other resources

These are essentially different streams of data that are getting ingested into Sentinel, and of course the more data ingested, the more expensive sentinel is. Determing which data will be ingested into Sentinel is the first step. 


After this, its time to design a Sentinel Workspace. 

When planning your Microsoft Sentinel workspace deployment, you must also design your Log Analytics workspace architecture. Decisions about the workspace architecture are typically driven by business and technical requirements. things to consider include... 

Whether you'll use a single tenant or multiple tenants
Any compliance requirements you have for data collection and storage
How to control access to Microsoft Sentinel data
Cost implications for different scenarios

We will go into more detail in a future space about workspace architecture. 





## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](link)

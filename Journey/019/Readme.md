Azure Blob Storage Tiers

![1_3fTyortCSpUIYm7VPuFvIQ](https://user-images.githubusercontent.com/102994059/206301634-78877b1e-ba9a-47f2-985a-edee206ca1ce.png)


☁️☁️☁️ Why do we have Storage Tiers in Azure?? 

To manage costs for your expanding storage needs, it can be helpful to organize your data based on how frequently it will be accessed and how long it will be retained.

☁️☁️☁️ What are the different storage tiers?

Hot tier - An online tier optimized for storing data that is accessed or modified frequently. The hot tier has the highest storage costs, but the lowest access costs.

Cool tier - An online tier optimized for storing data that is infrequently accessed or modified. Data in the cool tier should be stored for a minimum of 30 days. The cool tier has lower storage costs and higher access costs compared to the hot tier.

Archive tier - An offline tier optimized for storing data that is rarely accessed, and that has flexible latency requirements, on the order of hours. Data in the archive tier should be stored for a minimum of 180 days.


☁️☁️☁️ Online Storage Tiers

The hot and cool tiers are Online storge tiers. This means they can be accessed at any time. 

☁️☁️☁️ Archive access tier

The Archive access tier can NOT be accessed immediately, whenver you want. This data needs to be "rehydrated" by azure before you can access/modify the data. This can take several hours or longer. The advantage to this is it is the cheapest way to store data in Azure, and ideal for data rarely accessed. 
## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[linkedin post](https://www.linkedin.com/posts/andrew-leddy_100daysofcloud-activity-7006372665338777600-x88F?utm_source=share&utm_medium=member_desktop)

A Deeper Dive into KQL 


![image](https://user-images.githubusercontent.com/102994059/214450345-f3fba62c-3d03-4b4f-88eb-f7703774d45c.png)

ABOVE---- as you can see, some of the KQL can be edited and played around with simply by using the GUI

The left area is a reference list of the tables in the environment.

The bottom area is the Query Results 

Common Operators 

☁️☁️☁️Search

☁️☁️☁️Where

  SecurityEvent
| where TimeGenerated > ago(1d)

SecurityEvent
| where TimeGenerated > ago(1h) and EventID == "4624"

SecurityEvent
| where TimeGenerated > ago(1h)
| where EventID == 4624
| where AccountType =~ "user"

SecurityEvent | where EventID in (4624, 4625)

☁️☁️☁️ let 
  let timeOffset = 7d;
let discardEventId = 4688;
SecurityEvent
| where TimeGenerated > ago(timeOffset*2) and TimeGenerated < ago(timeOffset)
| where EventID != discardEventId

☁️☁️☁️ Extend

SecurityEvent
| where ProcessName != "" and Process != ""
| extend StartDir =  substring(ProcessName,0, string_size(ProcessName)-string_size(Process))



☁️☁️☁️ Order by 
SecurityEvent
| where ProcessName != "" and Process != ""
| extend StartDir =  substring(ProcessName,0, string_size(ProcessName)-string_size(Process))
| order by StartDir desc, Process asc


☁️☁️☁️ Project Operators 

Operator	Description
project	Select the columns to include, rename or drop, and insert new computed columns.
project-away	Select what columns from the input to exclude from the output.
project-keep	Select what columns from the input to keep in the output.
project-rename	Select the columns to rename in the resulting output.
project-reorder	Set the column order in the resulting output.





## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[linkedin post](https://www.linkedin.com/feed/update/urn:li:share:7023803762947325952/)

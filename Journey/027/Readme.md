Kusto Query Language

KQL is the language used to query the log data in the Log Analytics workspace. In Microsoft Sentinel, the Logs page provides access to the query window. The query window allows you to run queries, save queries, run saved queries, create a new alert rule, and export. The left side provides a list of tables and related table fields. To run a query, enter the query text and press the run button. Query results appear in the bottom section of the form.




![KQL](https://user-images.githubusercontent.com/102994059/211962000-f3129f42-9ded-4349-8cea-3930945097b0.png)


Microsoft Sentinel has Analytic Rules that will generate Alerts and Incidents based on querying the tables within Log Analytics. The primary tables to manage alerts and incidents are SecurityAlert and SecurityIncident. Microsoft Sentinel provides tables to be a repository of indicators and watchlists.


Table	Description
SecurityAlert---	Contains Alerts Generated from Sentinel Analytical Rules. Also, it could include Alerts created directly from a Sentinel Data Connector
SecurityIncident---	Alerts can generate Incidents. Incidents are related to Alert(s).
ThreatIntelligenceIndicator---	Contains user-created or data connector ingested Indicators such as File Hashes, IP Addresses, Domains
Watchlist---	A Microsoft Sentinel watchlist contains imported data.


THese are just the simplest tables, and the most basic KQL. Learning KQL is essenitial for a Azure Security Operations Analyst



## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](https://www.linkedin.com/posts/andrew-leddy_100daysofcloud-activity-7019128028794388480-eyHh?utm_source=share&utm_medium=member_desktop)

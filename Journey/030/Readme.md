ADVANCED HUNTING 

Advanced hunting is a query-based threat-hunting tool that lets you explore up to 30 days of raw data


☁️☁️☁️  The advanced hunting capability supports queries that check a broader data set from:

Microsoft Defender for Endpoint

Microsoft Defender for Office 365

Microsoft Defender for Cloud Apps

Microsoft Defender for Identity



☁️☁️☁️ USING KQL FOR THREAT HUNTING

The sample query below counts the number of unique devices (DeviceId) with antivirus detections and uses this to find only those devices with more than five detections. To return the latest Timestamp and the corresponding ReportId, it uses the summarize operator with the arg_max function.

DeviceEvents
| where Timestamp > ago(7d)
| where ActionType == "AntivirusDetection"
| summarize (Timestamp, ReportId)=arg_max(Timestamp, ReportId), count() by DeviceId
| where count_ > 5




## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](https://www.linkedin.com/posts/andrew-leddy_100daysofcloud-activity-7020830310841876481-TZeJ?utm_source=share&utm_medium=member_desktop)

# Lab 9: Dashboard Token Drilldown

## Description
This lab demonstrates how to perform a Splunk detection or engineering task. It simulates a real SOC task using Splunk Enterprise or Splunk Cloud.

## Key Skills Practiced
- ✅ Writing custom SPL queries
- ✅ Building dashboards or alerts
- ✅ Using lookups or workflow actions
- ✅ Practicing detection engineering concepts

## SPL Example
```spl
index=windows_logs sourcetype=csv
| stats count by user
# Token setup used for drilldown to detail panel
```

## Try It Yourself

① Upload sample logs (if applicable) using "Add Data" in Splunk.  
② Open the Search & Reporting app.  
③ Paste the SPL query and run it.  
④ Save the search as a report, alert, or dashboard panel.  
⑤ Visualize, enrich, or correlate events as needed.

## Screenshots
Save your visual output here:

![Lab 9 Screenshot](Lab9.png)

## Notes
This lab is designed to be modular. You can enhance it with additional SPL, saved searches, or dashboard panels as your skills grow.

# Azure Sentinel (SIEM) 

**DRAFT**
- Summary:
  - A VM in Azure was configured to be a honeypot.
  - Firewalls were disabled so attacks could occur and be monitored.
  - A log repository was established in Azure Log Analytics Workspace.
  - Using a powershell script, I was able to take data from Windows Event Viewer and have a third party API determine geolocation data.
  - Data was sent to Azure for mapping and analysis.
  - In Azure Log Analytics Workspace, I created a custom log named "failed RDP with geo"
  - Extract relevant data (username, IP address, country, timestamp) from the raw log entries.
  - Point of the lab was to visualize and analyze failed login attempts in Azure Sentinel.
  - Extracted data was used to create a map showcasing global cyber attack attempts on the configured honeypot.
 
  - TBC...

  *All thanks and credit for this lab goes to Josh Madakor*

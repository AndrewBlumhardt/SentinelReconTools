# SentinelReconTools
Sentinel Recon Tools Workbook
author: Andrew Blumhardt

This workbook provides eleven tabs that simplified Sentinel table exploration:

The **Simple Search** defaults to all tables if no tables are selected. The global search works best with short time durations. Longer durations can cause the query to error out. Select one or more tables for queries over longer durations.

**Table Explorer** is designed to help you better understand the data in your tables. Each table, column, and vaule is easily sorted by volume.

**Security Event Viewer**. Start by setting the time range above and the optional time brush. Each election is cumulative. Best if you select from 1-2 filter categories at a time.

**Windows Event Explorer**. Set the severity and optional timebrush. Each selection is cumulative. Best if you select from 1-2 filter categories at a time.

The **Security Audit Assessment** attempts to verify your Windows Security Audit Policy based on the event IDs collected. Windows Security Events are primarily the result of audit policy. This workbook can help to identify noisy policy configurations and potential audit gaps. 

**Azure Activity Log Viewer**. Start by setting the time range above and the optional time brush. Each selection is cumulative. Best if you select from 1-2 filter categories at a time.

**Azure Active Directory Log Viewer**. Start by setting the time range above and the optional time brush. Select the AAD log table followed by one or more item of interest. Each selection is cumulative. Best if you select from 1-2 filter categories at a time.

**Security Alert Viewer**. The initial set of tiles represents top alert and incident activity. The first tile displays the alert-to-incident ratio. This is a good indicator of alert aggregation. A low or near 1:1 ratio is an indicator of insufficient alert aggregation.

**CEF Log Explorer**. Start by selecting a timespan and one or more device vendor. Each selection is cumulative. Best if you select from 1-2 filter categories at a time.

**Syslog Explorer**. Start by selecting a timespan and one or more device vendor. Each selection is cumulative. Best if you select from 1-2 filter categories at a time.

**Agent Health Viewer**. The following workbooks shows agent health for connected Linux and Windows agents. Optional extension to view Defender for Cloud and Defender for Endpoint status. Time range must exceed the threshold value.

[Soon to be published on the official Sentinel repo](https://github.com/Azure/Azure-Sentinel/tree/master/Workbooks)

## Screenshots

![Version 1 Black](https://github.com/AndrewBlumhardt/SentinelReconTools/blob/main/Images/SentinelWorkspaceReconToolsBlack.png)

![Version 1 White](https://github.com/AndrewBlumhardt/SentinelReconTools/blob/main/Images/SentinelWorkspaceReconToolsWhite.png)

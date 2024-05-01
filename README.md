# Microsoft-eventlog-mindmap

## Project purpose
**Microsoft eventlog mindmap** provides an overview on well-known Microsoft products and solutions, as well as their auditing capacities. It enables defenders to enhance visibility on monitored environments for purposes like:
* Log collection (eg: into a SIEM)
* Threat hunting
* Incident response
* Forensic
* Troubleshooting

## Active mindmaps
The following mindmaps are currently provided (PDF/PNG/SVG formats):
* Windows OS auditing baseline
* Windows Server roles auditing (includes SQL Server and Advanced Threat Analytics)
* Active Directory (ADDS) auditing
* Microsoft Azure auditing
* Exchange Server 2016/2019 auditing
* Exchange email forwarding hunting

# Windows OS event logs
This map provides an overview of the native Event logs shipped in Windows OS. They are classified into different categories (network, security, application,...) and their related auditing settings.
![](/windows-auditing-baseline-map/windows-auditing-baseline-map.png)

# Windows Server roles event logs
This map provides an overview of the different Event logs and auditing capacities provided by Windows Server roles (ADCS, DHCP, DNS, OCSP, IIS, NPS, ADFS, MSSQL, RDS...).
![](/windows-server-roles-map/windows-server-roles-map.png)

# Active Directory event logs
This map provides an overview of the different Event logs and auditing capacities provided by Active Directory (ADDS) role.
![](/active-directory-map/active-directory-map.png)

# Exchange Server 2016/2019 event logs
This map provides an overview of the different data sources provided by Exchange Server.
![](/exchange-server-map/exchange-server-map.png)

# Exchange email rule hunting
This map provides an overview of the different hunting capacities regarding Exchange email compromise rules abused in BEC attacks.
![](/exchange-email-compromise-map/exchange-email-compromise.png)

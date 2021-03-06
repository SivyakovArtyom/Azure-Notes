# Azure-Notes
A list of usefull links, url, references, docs

## MS Learn
https://docs.microsoft.com/en-us/learn/

### Webinars
https://techcommunity.microsoft.com/t5/security-privacy-compliance/security-community-webinars/m-p/927888

### Tips for learning Azure in the new year
https://azure.microsoft.com/en-us/blog/tips-for-learning-azure-in-the-new-year/


## ZeroTrust
### Implementing a Zero Trust security model at Microsoft
https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE3w93r

## Integration between Azure Ad Identity Protection through API with SIEM solutions
https://docs.microsoft.com/en-us/azure/active-directory/identity-protection/overview-identity-protection
https://docs.microsoft.com/en-us/azure/active-directory/identity-protection/howto-identity-protection-graph-api

## Integration of MBAM with new Configuration Manager Current Branch versions for Bitlocker Management
https://www.youtube.com/watch?v=JK7v4b6Fi-0 Part1
https://www.niallbrady.com/2019/12/10/learn-about-mbam-integration-in-microsoft-endpoint-configuration-manager-version-1910-part-2-configure-portals/ 
https://www.niallbrady.com/2019/12/14/learn-about-mbam-in-microsoft-endpoint-configuration-manager-version-1910-part-3-customize-the-portals/ 
https://www.niallbrady.com/2019/12/17/learn-about-mbam-in-microsoft-endpoint-configuration-manager-version-1910-part-4-enforce-encryption/ 


# Windows Defender ATP
## Windows Defender AV + Group Policy Settings (including Turning Auto Exclusions) more details here
https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-defender-antivirus/use-group-policy-windows-defender-antivirus 
https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-defender-antivirus/configure-exclusions-windows-defender-antivirus

## Other device capabilities with Advanced Hunting and PowerBI
a.	https://techcommunity.microsoft.com/t5/Microsoft-Defender-ATP/Advanced-hunting-updates-USB-events-machine-level-actions-and/ba-p/824152 
b.	https://techcommunity.microsoft.com/t5/Microsoft-Defender-ATP/Create-custom-reports-using-Microsoft-Defender-ATP-APIs-and/ba-p/1007684
c.	https://github.com/microsoft/MDATP-PowerBI-Templates

## Defender ATP USB capabilities with Intune 
https://docs.microsoft.com/en-us/windows/security/threat-protection/device-control/control-usb-devices-using-intune

## Folder exclusions for some windows databases
https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-defender-antivirus/configure-server-exclusions-windows-defender-antivirus

# Azure Updates
https://azure.microsoft.com/en-us/updates/

# Azure Monitor
## Temprorary
https://docs.microsoft.com/en-us/azure/azure-monitor/platform/diagnostic-settings 

# Security
## Impersonating Office 365 Users With Mimikatz
https://www.dsinternals.com/en/impersonating-office-365-users-mimikatz/

# AZ-500
## References:
-	Microsoft Security Development Lifecycle: https://www.microsoft.com/en-us/securityengineering/sdl/
-	Microsoft Binskim: https://github.com/Microsoft/binskim
-	Attack surface analyzer: https://www.microsoft.com/en-us/download/details.aspx?id=58105
-	Microsoft Security Response Center: https://www.microsoft.com/en-us/msrc?rtc=1
-	Azure Security Center Github repo: https://github.com/Azure/Azure-Security-Center
-	WinSrv AD events: https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/plan/appendix-l--events-to-monitor
-	CIS Benchmark Azure: https://www.cisecurity.org/benchmark/azure/
-	Azure Automation: https://docs.microsoft.com/en-us/azure/automation/

The runbook to watch for event IDs in an Azure Virtual Machine, can be found here https://gallery.technet.microsoft.com/scriptcenter/Sample-monitor-runbook-to-28b5ad6e#content. The PScommand for pulling event id’s is Get-EventLog.

AKS planning:
https://techcommunity.microsoft.com/t5/premier-field-engineering/azure-kubernetes-service-cluster-capacity-planning/ba-p/1474990

1.	Azure AD Built-in Role assignments:https://docs.microsoft.com/en-us/azure/active-directory/users-groups-roles/directory-assign-admin-roles
2.	Azure AD Deployment Plans: https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-deployment-plans 
3.	Azure Architecture: https://docs.microsoft.com/en-us/azure/architecture/ 
4.	Azure Architecture - Naming Conventions: https://docs.microsoft.com/en-us/azure/architecture/best-practices/naming-conventions 
5.	Azure Updates (released, preview, planned): https://azure.microsoft.com/en-us/updates/
6.	Log Analytics playground: https://portal.loganalytics.io/demo 
7.	SysInternals Tool kit: https://docs.microsoft.com/en-us/sysinternals/ 
8.	3rd party site – tests, info, etc: http://www.azurespeed.com/ 
9.	Azure Certification & Exams: https://www.microsoft.com/en-us/learning/azure-exams.aspx
10.	Azure Certification self-assessment aids (and great portal for Azure stuff😊): https://build5nines.com/free-oss-exam-self-assessment-tool/
11.	Azure Certification Data Sheet (PDF file): https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RWtQJJ
12.	Ultimate Azure Resources repository: aka.ms/Azure/Shortcuts 
13.	Azure Policy: https://docs.microsoft.com/en-us/azure/governance/policy/ 
14.	Azure Blueprint Samples: https://docs.microsoft.com/en-us/azure/governance/blueprints/samples/ 
15.	Podcasts, blogs, sites: Azure Friday, Azure Mechanics
16.	Presentation files, materials and additional reading: 
•	AZ 500 slides: https://tinyurl.com/yc3azjoa 

PS reporting on MFA users scripts:
1.	https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-reporting#powershell-reporting-on-users-registered-for-mfa
2.	https://gallery.technet.microsoft.com/Export-Office-365-Users-81747c73

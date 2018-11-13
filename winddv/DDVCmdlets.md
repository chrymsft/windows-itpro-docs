---
Module Name: DDVCmdlets
Module Guid: 00000000-0000-0000-0000-000000000000
Download Help Link: {{Please enter FwLink manually}}
Help Version: 0.1.0.2
Locale: en-US
---

# DDVCmdlets Module
## Description
View the Windows diagnostic data collected by Microsoft from your local device. 

## DDVCmdlets Cmdlets
### [Disable-DiagnosticDataViewing](Disable-DiagnosticDataViewing.md)
Disables diagnostic data viewing.

### [Enable-DiagnosticDataViewing](Enable-DiagnosticDataViewing.md)
Enables diagnostic data viewing.

### [Get-DiagnosticData](Get-DiagnosticData.md)
Fetches historical Windows Diagnostic Data uploaded by this machine.

### [Get-DiagnosticDataTypes](Get-DiagnosticDataTypes.md)
Fetches the mapping of diagnostic data type identifiers to their corresponding descriptions.

### [Get-DiagnosticDataViewingSetting](Get-DiagnosticDataViewingSetting.md)
Fetches whether diagnostic data viewing is currently enabled or disabled.

### [Get-DiagnosticStoreCapacity](Get-DiagnosticStoreCapacity.md)
Fetches the current diagnostic store capacity.
Parameter \[-Size\] returns the diagnostic store size capacity in megabytes.
Parameter \[-Time\] returns the diagnostic store capacity in days.
The default diagnostic data store size capacity is 1024 MB.
The default time capacity is 30 days.

### [Set-DiagnosticStoreCapacity](Set-DiagnosticStoreCapacity.md)
Sets the diagnostic store time and size capacity.


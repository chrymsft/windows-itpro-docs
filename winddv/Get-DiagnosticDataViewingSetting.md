---
external help file: DDVCmdlets.dll-Help.xml
Module Name: DDVCmdlets
online version:
schema: 2.0.0
---

# Get-DiagnosticDataViewingSetting

## SYNOPSIS
Fetches whether diagnostic data viewing is currently enabled or disabled.

## SYNTAX

```
Get-DiagnosticDataViewingSetting [<CommonParameters>]
```

## DESCRIPTION
This cmdlet returns the current state of diagnostic data viewing.
This state indicates whether diagnostic data viewing is enabled for this device.
Once enabled, the device henceforth will start recording each diagnostic data event uploaded to Microsoft, where the total history is limited by the diagnostic store capacity.
If disabled, this tool will throw an error.

## EXAMPLES

### EXAMPLE 1
```
Get-DiagnosticDataViewingState
```

Checks if Diagnostic Data Viewing is enabled.

## PARAMETERS

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### System.String
## NOTES

## RELATED LINKS

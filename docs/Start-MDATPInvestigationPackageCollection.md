---
external help file: PSMDATP-help.xml
Module Name: PSMDATP
online version:
schema: 2.0.0
---

# Start-MDATPInvestigationPackageCollection

## SYNOPSIS
Start-MDATPInvestigationPackageCollection

## SYNTAX

### DeviceName
```
Start-MDATPInvestigationPackageCollection -DeviceName <String> [-Comment <String>] [-MTPConfigFile <String>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### DeviceID
```
Start-MDATPInvestigationPackageCollection -DeviceID <String> [-Comment <String>] [-MTPConfigFile <String>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Start-MDATPInvestigationPackageCollection initiates the collection of an investigation package

## EXAMPLES

### EXAMPLE 1
```
Start-MDATPInvestigationPackageCollection -DeviceName computer02
```

This command starts the collection of the investigation package on device computer02

## PARAMETERS

### -DeviceName
Computername of the device

```yaml
Type: String
Parameter Sets: DeviceName
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceID
The unique device ID of the device

```yaml
Type: String
Parameter Sets: DeviceID
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Comment
Comment that is added to the request, if no comment is provided the default commment 'submitted by automation' is used.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MTPConfigFile
API Configuration file

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable.
For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES
Version:        1.0
Author:         Alex Verboon
Creation Date:  17.03.2020
Purpose/Change: Initial script development

## RELATED LINKS

---
external help file: RobocopyPS-help.xml
Module Name: RobocopyPS
online version:
schema: 2.0.0
---

# Remove-RoboFolder

## SYNOPSIS
Remove folder with help of Robocopy

## SYNTAX

```
Remove-RoboFolder [-Target] <Object> [-BackupMode] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Creates a temporary folder in users TEMP directory, mirror the temp folder to the Path specificed.
Removes the temp folder when done

## EXAMPLES

### EXAMPLE 1
```
Remove-RoboFolder -Path "C:\temp"
```

## PARAMETERS

### -BackupMode
{{ Fill BackupMode Description }}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
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

### -Target
Param1 help description

```yaml
Type: Object
Parameter Sets: (All)
Aliases: Destination, Path

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES
General notes

## RELATED LINKS
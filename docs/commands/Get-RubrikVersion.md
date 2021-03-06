---
external help file: Rubrik-help.xml
Module Name: Rubrik
online version: http://rubrikinc.github.io/rubrik-sdk-for-powershell/reference/Get-RubrikVersion.html
schema: 2.0.0
---

# Get-RubrikVersion

## SYNOPSIS
Connects to Rubrik and retrieves the current version

## SYNTAX

```
Get-RubrikVersion [[-id] <String>] [[-Server] <String>] [[-api] <String>] [<CommonParameters>]
```

## DESCRIPTION
The Get-RubrikVersion cmdlet will retrieve the version of code that is actively running on the system.

## EXAMPLES

### EXAMPLE 1
```
Get-RubrikVersion
```

This will return the running version on the Rubrik cluster

## PARAMETERS

### -id
ID of the Rubrik cluster or me for self

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: Me
Accept pipeline input: False
Accept wildcard characters: False
```

### -Server
Rubrik server IP or FQDN

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 2
Default value: $global:RubrikConnection.server
Accept pipeline input: False
Accept wildcard characters: False
```

### -api
API version

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: $global:RubrikConnection.api
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES
Written by Chris Wahl for community usage
Twitter: @ChrisWahl
GitHub: chriswahl

## RELATED LINKS

[http://rubrikinc.github.io/rubrik-sdk-for-powershell/reference/Get-RubrikVersion.html](http://rubrikinc.github.io/rubrik-sdk-for-powershell/reference/Get-RubrikVersion.html)


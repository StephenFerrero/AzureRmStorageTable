---
external help file: AzureRmStorageTableCoreHelper-help.xml
Module Name: azurermstoragetable
online version:
schema: 2.0.0
---

# Get-AzTableRowByPartitionKey

## SYNOPSIS
Returns one or more rows/entities based on Partition Key

## SYNTAX

```powershell
Get-AzTableRowByPartitionKey [-Table] <Object> [-PartitionKey] <String> [[-Top] <Int32>] [<CommonParameters>]
```

## DESCRIPTION
Returns one or more rows/entities based on Partition Key

## EXAMPLES

### EXAMPLE 1
```powershell
# Getting rows by partition Key
Get-AzTableRowByPartitionKey -Table $Table -PartitionKey "mypartitionkey"
```

### EXAMPLE 2
```powershell
# Getting rows by partition key with a maximum number returned
Get-AzTableRowByPartitionKey -Table $Table -PartitionKey "mypartitionkey" -Top 10
```

## PARAMETERS

### -Table
Table object of type Microsoft.Azure.Cosmos.Table.CloudTable to retrieve entities

```yaml
Type: Object
Parameter Sets: (All)
Aliases:

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PartitionKey
Identifies the table partition

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Top
Return only the first n rows from the query

```yaml
Type: Int32
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

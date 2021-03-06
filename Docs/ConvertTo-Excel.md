---
external help file: PSWriteExcel-help.xml
Module Name: PSWriteExcel
online version:
schema: 2.0.0
---

# ConvertTo-Excel

## SYNOPSIS
{{Fill in the Synopsis}}

## SYNTAX

```
ConvertTo-Excel [[-FilePath] <String>] [[-Excel] <ExcelPackage>] [[-ExcelWorkSheetName] <String>]
 [[-DataTable] <Object>] [[-Option] <String>] [-AutoFilter] [-AutoFit] [-FreezeTopRow] [-FreezeFirstColumn]
 [-FreezeTopRowFirstColumn] [[-FreezePane] <Int32[]>] [-Transpose] [[-TransposeSort] <String>] [-OpenWorkBook]
 [<CommonParameters>]
```

## DESCRIPTION
{{Fill in the Description}}

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -AutoFilter
{{Fill AutoFilter Description}}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AutoFit
{{Fill AutoFit Description}}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: Autosize

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DataTable
{{Fill DataTable Description}}

```yaml
Type: Object
Parameter Sets: (All)
Aliases: TargetData

Required: False
Position: 3
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Excel
{{Fill Excel Description}}

```yaml
Type: ExcelPackage
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExcelWorkSheetName
{{Fill ExcelWorkSheetName Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases: Name, WorksheetName

Required: False
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FilePath
{{Fill FilePath Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases: path

Required: False
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FreezeFirstColumn
{{Fill FreezeFirstColumn Description}}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FreezePane
{{Fill FreezePane Description}}

```yaml
Type: Int32[]
Parameter Sets: (All)
Aliases:

Required: False
Position: 5
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FreezeTopRow
{{Fill FreezeTopRow Description}}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FreezeTopRowFirstColumn
{{Fill FreezeTopRowFirstColumn Description}}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OpenWorkBook
{{Fill OpenWorkBook Description}}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Option
{{Fill Option Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases:
Accepted values: Replace, Skip, Rename

Required: False
Position: 4
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Transpose
{{Fill Transpose Description}}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: Rotate, RotateData, TransposeColumnsRows, TransposeData

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TransposeSort
{{Fill TransposeSort Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases:
Accepted values: ASC, DESC, NONE

Required: False
Position: 6
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### System.Object

## OUTPUTS

### System.Object
## NOTES

## RELATED LINKS

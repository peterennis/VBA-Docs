---
title: HasDataTable property (Excel Graph)
keywords: vbagr10.chm5207470
f1_keywords:
- vbagr10.chm5207470
ms.prod: excel
api_name:
- Excel.HasDataTable
ms.assetid: 52d965ca-e4cf-35d5-0ac6-5a6144aedff0
ms.date: 04/11/2019
localization_priority: Normal
---


# HasDataTable property (Excel Graph)

**True** if the chart has a data table. Read/write **Boolean**.

## Syntax

_expression_.**HasDataTable**

_expression_ Required. An expression that returns one of the objects in the **Applies To** list.

## Example

This example causes the chart data table to be displayed with an outline border and no cell borders.

```vb
With myChart 
 .HasDataTable = True 
 With .DataTable 
 .HasBorderHorizontal = False 
 .HasBorderVertical = False 
 .HasBorderOutline = True 
 End With 
End With
```

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]
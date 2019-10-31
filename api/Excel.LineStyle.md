---
title: LineStyle property (Excel Graph)
keywords: vbagr10.chm3077078
f1_keywords:
- vbagr10.chm3077078
ms.prod: excel
api_name:
- Excel.LineStyle
ms.assetid: 4783a76a-9e73-c605-ade5-be8fec821b1d
ms.date: 04/11/2019
localization_priority: Normal
---


# LineStyle property (Excel Graph)

Returns or sets the line style for the border. Read/write **[XlLineStyle](excel.xllinestyle.md)**.

## Syntax

_expression_.**LineStyle**

_expression_ Required. An expression that returns one of the objects in the **Applies To** list.

## Example

This example puts a border around the chart area and the plot area.

```vb
With myChart 
 .ChartArea.Border.LineStyle = xlDashDot 
 With .PlotArea.Border 
 .LineStyle = xlDashDotDot 
 .Weight = xlThick 
 End With 
End With
```

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]
---
title: Background property (Excel Graph)
keywords: vbagr10.chm65716
f1_keywords:
- vbagr10.chm65716
ms.prod: excel
api_name:
- Excel.Background
ms.assetid: f20b2bfe-4f10-8300-be78-7b37135445a4
ms.date: 04/09/2019
localization_priority: Normal
---


# Background property (Excel Graph)

Returns or sets the text background type. This property is used only for text on charts. Read/write **[XlBackground](excel.xlbackground.md)**.


## Syntax

_expression_.**Background**

_expression_ Required. An expression that returns one of the objects in the **Applies To** list.

## Example

This example adds a chart title and then sets the font size and background type for the title.

```vb
With myChart 
 .HasTitle = True 
 .ChartTitle.Text = "1995 Rainfall Totals by Month" 
 With .ChartTitle.Font 
 .Size = 10 
 .Background = xlBackgroundTransparent 
 End With 
End With
```

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]
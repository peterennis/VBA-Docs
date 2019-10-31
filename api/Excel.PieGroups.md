---
title: PieGroups method (Excel Graph)
keywords: vbagr10.chm65549
f1_keywords:
- vbagr10.chm65549
ms.prod: excel
api_name:
- Excel.PieGroups
ms.assetid: f7fd5497-f7a0-6c28-1a59-9e6f37a0885e
ms.date: 04/09/2019
localization_priority: Normal
---


# PieGroups method (Excel Graph)

On a 2D chart, returns an object that represents either a single pie chart group or a collection of pie chart groups.

## Syntax

_expression_.**PieGroups** (_Index_)

_expression_ Required. An expression that returns one of the objects in the **[ChartGroups](excel.chartgroups(collection).md)** collection.

## Parameters

|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
|_Index_ | Optional |**Variant**| Specifies the chart group.|

## Example

This example sets pie group one to use a different color for each data marker. The example should be run on a 2D chart.

```vb
myChart.PieGroups(1).VaryByCategories = True
```



[!include[Support and feedback](~/includes/feedback-boilerplate.md)]
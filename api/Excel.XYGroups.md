---
title: XYGroups method (Excel Graph)
keywords: vbagr10.chm3077639
f1_keywords:
- vbagr10.chm3077639
ms.prod: excel
api_name:
- Excel.XYGroups
ms.assetid: d334382a-8d27-2b35-4306-a16f5fa13c89
ms.date: 04/09/2019
localization_priority: Normal
---


# XYGroups method (Excel Graph)

On a 2D chart, returns an object that represents either a single scatter chart group or a collection of the scatter chart groups.

## Syntax

_expression_.**XYGroups** (_Index_)

_expression_ Required. An expression that returns one of the objects in the **Applies To** list.

## Parameters

|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
|_Index_ | Optional |**Variant**| Specifies the chart group.|

## Example

This example sets X-Y group (scatter group) one to use a different color for each data marker. The example should be run on a 2D chart.

```vb
myChart.XYGroups(1).VaryByCategories = True
```

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]
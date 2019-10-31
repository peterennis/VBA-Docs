---
title: WebBrowserControl.Width property (Access)
keywords: vbaac10.chm14372
f1_keywords:
- vbaac10.chm14372
ms.prod: access
api_name:
- Access.WebBrowserControl.Width
ms.assetid: 0a55e8d9-c53e-0afe-b41e-31c1e3f8b10e
ms.date: 02/27/2019
localization_priority: Normal
---


# WebBrowserControl.Width property (Access)

Gets or sets the width of the specified object in [twips](../language/glossary/vbe-glossary.md#twip). Read/write **Integer**.


## Syntax

_expression_.**Width**

_expression_ A variable that represents a **[WebBrowserControl](Access.WebBrowserControl.md)** object.


## Remarks

For report controls, you can set the **Width** property when you print or preview a report only by using a macro or an event procedure specified in a section's **OnFormat** event property setting.

You can't set this property for an object after the print process has started.

Microsoft Access automatically sets the **Width** property when you create or size a control or when you size a window in form Design view or report Design view.

The width of forms and reports is measured from the inside of their borders. The width of controls is measured from the center of their borders so that controls with different border widths align correctly. 

The margins for forms and reports are set in the **Page Setup** dialog box, available by choosing **Page Setup** on the **File** menu.



[!include[Support and feedback](~/includes/feedback-boilerplate.md)]
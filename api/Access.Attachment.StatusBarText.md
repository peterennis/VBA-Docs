---
title: Attachment.StatusBarText property (Access)
keywords: vbaac10.chm14012
f1_keywords:
- vbaac10.chm14012
ms.prod: access
api_name:
- Access.Attachment.StatusBarText
ms.assetid: 9d947d11-edb1-947a-df0c-727ef9b1599a
ms.date: 02/07/2019
localization_priority: Normal
---


# Attachment.StatusBarText property (Access)

You can use the **StatusBarText** property to specify the text that is displayed in the status bar when a control is selected. Read/write **String**.


## Syntax

_expression_.**StatusBarText**

_expression_ A variable that represents an **[Attachment](Access.Attachment.md)** object.


## Remarks

The **StatusBarText** property applies only to controls on a form, and not to controls on a report.

You set the **StatusBarText** property by using a string expression up to 255 characters long. The length of the text that you can display in the status bar depends on your computer hardware and video display.

You can use the **StatusBarText** property to provide specific information about a control. For example, when a text box has the focus, a brief instruction can tell the user what kind of data to enter.

If you create a control by dragging a field from the field list, the value in a field's **Description** property is copied to the **StatusBarText** property.

> [!TIP] 
> You can also use the **ControlTipText** property to display a ScreenTip for a control.


[!include[Support and feedback](~/includes/feedback-boilerplate.md)]
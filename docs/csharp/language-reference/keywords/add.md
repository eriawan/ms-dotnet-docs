---
description: Learn how to create custom event accessors using add keyword in C#
title: "add keyword"
ms.date: 07/20/2015
f1_keywords: 
  - "add_CSharpKeyword"
helpviewer_keywords: 
  - "add event accessor [C#]"
ms.assetid: faf30b99-10e8-45cd-ab9a-57585d4d1d8d
---
# add (C# Reference)

The `add` contextual keyword is used to define a custom event accessor that is invoked when client code subscribes to your [event](./event.md). If you supply a custom `add` accessor, you must also supply a [remove](./remove.md) accessor.  
  
## Example  

The following example shows an event that has custom `add` and [remove](./remove.md) accessors. For the full example, see [How to implement interface events](../../programming-guide/events/how-to-implement-interface-events.md).
  
[!code-csharp[csrefKeywordsContextual#15](~/samples/snippets/csharp/VS_Snippets_VBCSharp/csrefKeywordsContextual/CS/csrefKeywordsContextual.cs#15)]
  
 You do not typically need to provide your own custom event accessors. The accessors that are automatically generated by the compiler when you declare an event are sufficient for most scenarios.  
  
## See also

- [Events](../../programming-guide/events/index.md)

# Pattern\.SurroundWordBoundary Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [SurroundWordBoundary(Object)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundWordBoundary_System_Object_) | Appends a pattern that matches spefified pattern surrounded with a word boundary\. |
| [SurroundWordBoundary(Object\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundWordBoundary_System_Object___) | Appends a pattern that matches specified content surrounded with a word boundary\. |

## SurroundWordBoundary\(Object\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundWordBoundary_System_Object_"></a>

### Summary

Appends a pattern that matches spefified pattern surrounded with a word boundary\.

```csharp
public QuantifiablePattern SurroundWordBoundary(object content)
```

### Parameters

**content**

A text to surround\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

## SurroundWordBoundary\(Object\[\]\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundWordBoundary_System_Object___"></a>

### Summary

Appends a pattern that matches specified content surrounded with a word boundary\.

```csharp
public QuantifiablePattern SurroundWordBoundary(params object[] content)
```

### Parameters

**content**

An object array that contains zero or more values any one of which has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

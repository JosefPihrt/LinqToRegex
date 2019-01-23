# Patterns\.Maybe Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Maybe(Object)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Maybe_System_Object_) | Returns a pattern that matches specified content zero or one time\. |
| [Maybe(Object, Object\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Maybe_System_Object_System_Object___) | Returns a pattern that matches any one specified element zero or one time\. |

## Maybe\(Object\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Maybe_System_Object_"></a>

### Summary

Returns a pattern that matches specified content zero or one time\.

```csharp
public static QuantifiedGroup Maybe(object content)
```

### Parameters

**content**

The content to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

## Maybe\(Object, Object\[\]\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Maybe_System_Object_System_Object___"></a>

### Summary

Returns a pattern that matches any one specified element zero or one time\.

```csharp
public static QuantifiedGroup Maybe(object first, params object[] others)
```

### Parameters

**first**

First element of a sequence that contains patterns any one of which has to be matched\.

**others**

Other elements of a sequence that contains patterns any one of which has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**first** is `null`\.

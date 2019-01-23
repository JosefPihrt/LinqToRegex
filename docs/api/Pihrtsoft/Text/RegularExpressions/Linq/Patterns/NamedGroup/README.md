# Patterns\.NamedGroup Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NamedGroup(String, Object)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NamedGroup_System_String_System_Object_) | Returns a named group with a specified name and content\. |
| [NamedGroup(String, Object\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NamedGroup_System_String_System_Object___) | Returns a named group with a specified name and content\. |

## NamedGroup\(String, Object\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NamedGroup_System_String_System_Object_"></a>

### Summary

Returns a named group with a specified name and content\.

```csharp
public static QuantifiablePattern NamedGroup(string name, object content)
```

### Parameters

**name**

A name of the group\.

**content**

The content to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

System\.[ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentexception)

**name** is not a valid regex group name\.

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**name** **content** is `null`\.

## NamedGroup\(String, Object\[\]\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NamedGroup_System_String_System_Object___"></a>

### Summary

Returns a named group with a specified name and content\.

```csharp
public static QuantifiablePattern NamedGroup(string name, params object[] content)
```

### Parameters

**name**

A name of the group\.

**content**

An object array that contains zero or more patterns any one of which has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

System\.[ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentexception)

**name** is not a valid regex group name\.

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**name** **content** is `null`\.

# Pattern\.Match Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Match(String)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Match_System_String_) | Searches a specified input string for the first occurrence of the current instance\. |
| [Match(String, RegexOptions)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Match_System_String_System_Text_RegularExpressions_RegexOptions_) | Searches a specified input string for the first occurrence of the current instance, using the specified matching options\. |

## Match\(String\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Match_System_String_"></a>

### Summary

Searches a specified input string for the first occurrence of the current instance\.

```csharp
public Match Match(string input)
```

### Parameters

**input**

The string to search for a match\.

### Returns

System\.Text\.RegularExpressions\.[Match](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.match)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**input** is `null`\.

## Match\(String, RegexOptions\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Match_System_String_System_Text_RegularExpressions_RegexOptions_"></a>

### Summary

Searches a specified input string for the first occurrence of the current instance, using the specified matching options\.

```csharp
public Match Match(string input, RegexOptions options)
```

### Parameters

**input**

The string to search for a match\.

**options**

A bitwise combination of the enumeration values that specify options for matching\.

### Returns

System\.Text\.RegularExpressions\.[Match](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.match)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**input** is `null`\.

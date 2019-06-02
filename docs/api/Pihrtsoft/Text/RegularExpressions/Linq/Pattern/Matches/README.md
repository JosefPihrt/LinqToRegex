# Pattern\.Matches Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Matches(String)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Matches_System_String_) | Searches the specified input string for all matches\. |
| [Matches(String, RegexOptions)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Matches_System_String_System_Text_RegularExpressions_RegexOptions_) | Searches the specified input string for all matches, using the specified matching options\. |

## Matches\(String\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Matches_System_String_"></a>

### Summary

Searches the specified input string for all matches\.

```csharp
public System.Text.RegularExpressions.MatchCollection Matches(string input)
```

### Parameters

**input**

The string to search for a match\.

### Returns

System\.Text\.RegularExpressions\.[MatchCollection](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.matchcollection)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**input** is `null`\.

## Matches\(String, RegexOptions\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Matches_System_String_System_Text_RegularExpressions_RegexOptions_"></a>

### Summary

Searches the specified input string for all matches, using the specified matching options\.

```csharp
public System.Text.RegularExpressions.MatchCollection Matches(string input, System.Text.RegularExpressions.RegexOptions options)
```

### Parameters

**input**

The string to search for a match\.

**options**

A bitwise combination of the enumeration values that specify options for matching\.

### Returns

System\.Text\.RegularExpressions\.[MatchCollection](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.matchcollection)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**input** is `null`\.


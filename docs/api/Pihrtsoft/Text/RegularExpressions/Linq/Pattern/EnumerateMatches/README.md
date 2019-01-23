# Pattern\.EnumerateMatches Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [EnumerateMatches(String)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_EnumerateMatches_System_String_) | Searches the specified input string and returns an enumerable collection of matches\. |
| [EnumerateMatches(String, RegexOptions)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_EnumerateMatches_System_String_System_Text_RegularExpressions_RegexOptions_) | Searches the specified input string and returns an enumerable collection of matches, using the specified matching options\. |

## EnumerateMatches\(String\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_EnumerateMatches_System_String_"></a>

### Summary

Searches the specified input string and returns an enumerable collection of matches\.

```csharp
public IEnumerable<Match> EnumerateMatches(string input)
```

### Parameters

**input**

The string to search for a match\.

### Returns

System\.Collections\.Generic\.[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<[Match](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.match)>

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**input** is `null`\.

## EnumerateMatches\(String, RegexOptions\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_EnumerateMatches_System_String_System_Text_RegularExpressions_RegexOptions_"></a>

### Summary

Searches the specified input string and returns an enumerable collection of matches, using the specified matching options\.

```csharp
public IEnumerable<Match> EnumerateMatches(string input, RegexOptions options)
```

### Parameters

**input**

The string to search for a match\.

**options**

A bitwise combination of the enumeration values that specify options for matching\.

### Returns

System\.Collections\.Generic\.[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<[Match](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.match)>

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**input** is `null`\.

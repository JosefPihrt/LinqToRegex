# RegexExtensions\.EnumerateMatches Method

[Home](../../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.Extensions\.[RegexExtensions](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [EnumerateMatches(Regex, String)](#Pihrtsoft_Text_RegularExpressions_Linq_Extensions_RegexExtensions_EnumerateMatches_System_Text_RegularExpressions_Regex_System_String_) | Searches the specified input string and returns enumerable collection of regular expression matches\. |
| [EnumerateMatches(Regex, String, Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Extensions_RegexExtensions_EnumerateMatches_System_Text_RegularExpressions_Regex_System_String_System_Int32_) | Searches the specified input string beginning at the specified position and returns enumerable collection of regular expression matches\. |
| [EnumerateMatches(Regex, String, Int32, Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Extensions_RegexExtensions_EnumerateMatches_System_Text_RegularExpressions_Regex_System_String_System_Int32_System_Int32_) | Searches the specified input string beginning at the specified position and searching only the specified number of characters and returns enumerable collection of regular expression matches\. |

## EnumerateMatches\(Regex, String\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Extensions_RegexExtensions_EnumerateMatches_System_Text_RegularExpressions_Regex_System_String_"></a>

### Summary

Searches the specified input string and returns enumerable collection of regular expression matches\.

```csharp
public static System.Collections.Generic.IEnumerable<System.Text.RegularExpressions.Match> EnumerateMatches(this System.Text.RegularExpressions.Regex regex, string input)
```

### Parameters

**regex**

The regular expression to be matched\.

**input**

The string to search for a match\.

### Returns

System\.Collections\.Generic\.[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<System\.Text\.RegularExpressions\.[Match](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.match)>

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**regex** or **input** is `null`\.

## EnumerateMatches\(Regex, String, Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Extensions_RegexExtensions_EnumerateMatches_System_Text_RegularExpressions_Regex_System_String_System_Int32_"></a>

### Summary

Searches the specified input string beginning at the specified position and returns enumerable collection of regular expression matches\.

```csharp
public static System.Collections.Generic.IEnumerable<System.Text.RegularExpressions.Match> EnumerateMatches(this System.Text.RegularExpressions.Regex regex, string input, int startAt)
```

### Parameters

**regex**

The regular expression to be matched\.

**input**

The string to search for a match\.

**startAt**

The position at which to start the search\.

### Returns

System\.Collections\.Generic\.[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<System\.Text\.RegularExpressions\.[Match](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.match)>

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**regex** or **input** is `null`\.

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**startAt** is less than zero or greater that the length of **input**\.

## EnumerateMatches\(Regex, String, Int32, Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Extensions_RegexExtensions_EnumerateMatches_System_Text_RegularExpressions_Regex_System_String_System_Int32_System_Int32_"></a>

### Summary

Searches the specified input string beginning at the specified position and searching only the specified number of characters and returns enumerable collection of regular expression matches\.

```csharp
public static System.Collections.Generic.IEnumerable<System.Text.RegularExpressions.Match> EnumerateMatches(this System.Text.RegularExpressions.Regex regex, string input, int beginning, int length)
```

### Parameters

**regex**

The regular expression to be matched\.

**input**

The string to search for a match\.

**beginning**

The position at which to start the search\.

**length**

A number of characters to be searched\.

### Returns

System\.Collections\.Generic\.[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<System\.Text\.RegularExpressions\.[Match](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.match)>

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**regex** or **input** is `null`\.

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**beginning** is less than zero or greater than the length of input\.


**length** is less than zero or greater then the length of input\.




**beginning** \+ **length** \- 1 is outside the range of input\.




# RegexExtensions\.EnumerateLengths\(Regex, String\) Method

[Home](../../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.Extensions\.[RegexExtensions](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Summary

Searches the specified input string for occurrence of the specified regular expression and returns an enumerable collection of matches lengths\.

```csharp
public static IEnumerable<int> EnumerateLengths(this Regex regex, string input)
```

### Parameters

**regex**

The regular expression to be matched\.

**input**

The string to search for a match\.

### Returns

System\.Collections\.Generic\.[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<[Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)>

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**regex** or **input** is `null`\.

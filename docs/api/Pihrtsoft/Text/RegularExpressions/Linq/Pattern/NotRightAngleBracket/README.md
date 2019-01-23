# Pattern\.NotRightAngleBracket Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotRightAngleBracket()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotRightAngleBracket) | Appends a pattern that matches a character that is not an right angle bracket \(greater\-than sign\)\. |
| [NotRightAngleBracket(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotRightAngleBracket_System_Int32_) | Appends a pattern that matches a specified number of characters that are not a right angle bracket \(greater\-than sign\)\. |

## NotRightAngleBracket\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotRightAngleBracket"></a>

### Summary

Appends a pattern that matches a character that is not an right angle bracket \(greater\-than sign\)\.

```csharp
public QuantifiablePattern NotRightAngleBracket()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

## NotRightAngleBracket\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotRightAngleBracket_System_Int32_"></a>

### Summary

Appends a pattern that matches a specified number of characters that are not a right angle bracket \(greater\-than sign\)\.

```csharp
public QuantifiedGroup NotRightAngleBracket(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

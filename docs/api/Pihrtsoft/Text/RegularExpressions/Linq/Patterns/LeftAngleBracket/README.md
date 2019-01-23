# Patterns\.LeftAngleBracket Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [LeftAngleBracket()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_LeftAngleBracket) | Returns a pattern that matches a left angle bracket \(less\-than sign\)\. |
| [LeftAngleBracket(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_LeftAngleBracket_System_Int32_) | Returns a pattern that matches a specified number of left angle brackets \(less\-than signs\)\. |

## LeftAngleBracket\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_LeftAngleBracket"></a>

### Summary

Returns a pattern that matches a left angle bracket \(less\-than sign\)\.

```csharp
public static CharPattern LeftAngleBracket()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[CharPattern](../../CharPattern/README.md)

## LeftAngleBracket\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_LeftAngleBracket_System_Int32_"></a>

### Summary

Returns a pattern that matches a specified number of left angle brackets \(less\-than signs\)\.

```csharp
public static QuantifiedGroup LeftAngleBracket(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

# Patterns\.ArabicDigit Method

[Home](../../../../../../README.md)

**Containing Type**: [Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [ArabicDigit()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_ArabicDigit) | Returns a pattern that matches an arabic digit\. |
| [ArabicDigit(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_ArabicDigit_System_Int32_) | Returns a pattern that matches a specified number of arabic digits\. |

## ArabicDigit\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_ArabicDigit"></a>

\
Returns a pattern that matches an arabic digit\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.CharGroup ArabicDigit()
```

### Returns

[CharGroup](../../CharGroup/README.md)

## ArabicDigit\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_ArabicDigit_System_Int32_"></a>

\
Returns a pattern that matches a specified number of arabic digits\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup ArabicDigit(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.


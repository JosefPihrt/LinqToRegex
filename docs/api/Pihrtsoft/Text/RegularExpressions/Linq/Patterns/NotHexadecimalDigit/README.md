# Patterns\.NotHexadecimalDigit Method

[Home](../../../../../../README.md)

**Containing Type**: [Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotHexadecimalDigit()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotHexadecimalDigit) | Returns a pattern that matches a character that is not a hexadecimal digit\. |
| [NotHexadecimalDigit(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotHexadecimalDigit_System_Int32_) | Returns a pattern that matches a character that is not a hexadecimal digit specified number of times\. |

## NotHexadecimalDigit\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotHexadecimalDigit"></a>

\
Returns a pattern that matches a character that is not a hexadecimal digit\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.CharGroup NotHexadecimalDigit()
```

### Returns

[CharGroup](../../CharGroup/README.md)

## NotHexadecimalDigit\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotHexadecimalDigit_System_Int32_"></a>

\
Returns a pattern that matches a character that is not a hexadecimal digit specified number of times\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup NotHexadecimalDigit(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.


# Pattern\.NotRightSquareBracket Method

[Home](../../../../../../README.md)

**Containing Type**: [Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotRightSquareBracket()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotRightSquareBracket) | Appends a pattern that matches a character that is not a right square bracket\. |
| [NotRightSquareBracket(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotRightSquareBracket_System_Int32_) | Appends a pattern that matches a specified number of characters that are not a right square bracket\. |

## NotRightSquareBracket\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotRightSquareBracket"></a>

\
Appends a pattern that matches a character that is not a right square bracket\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern NotRightSquareBracket()
```

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

## NotRightSquareBracket\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotRightSquareBracket_System_Int32_"></a>

\
Appends a pattern that matches a specified number of characters that are not a right square bracket\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup NotRightSquareBracket(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.


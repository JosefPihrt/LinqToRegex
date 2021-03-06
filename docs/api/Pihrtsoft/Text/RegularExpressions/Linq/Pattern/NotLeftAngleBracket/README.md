# Pattern\.NotLeftAngleBracket Method

[Home](../../../../../../README.md)

**Containing Type**: [Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotLeftAngleBracket()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotLeftAngleBracket) | Appends a pattern that matches a character that is not a left angle bracket \(less\-than sign\)\. |
| [NotLeftAngleBracket(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotLeftAngleBracket_System_Int32_) | Appends a pattern that matches a specified number of characters that are not a left angle bracket \(less\-than sign\)\. |

## NotLeftAngleBracket\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotLeftAngleBracket"></a>

\
Appends a pattern that matches a character that is not a left angle bracket \(less\-than sign\)\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern NotLeftAngleBracket()
```

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

## NotLeftAngleBracket\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotLeftAngleBracket_System_Int32_"></a>

\
Appends a pattern that matches a specified number of characters that are not a left angle bracket \(less\-than sign\)\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup NotLeftAngleBracket(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.


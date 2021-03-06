# Pattern\.CurlyBracket Method

[Home](../../../../../../README.md)

**Containing Type**: [Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [CurlyBracket()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_CurlyBracket) | Appends a pattern that matches left or right curly bracket\. |
| [CurlyBracket(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_CurlyBracket_System_Int32_) | Appends a pattern that matches left or right curly bracket specified number of times\. |

## CurlyBracket\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_CurlyBracket"></a>

\
Appends a pattern that matches left or right curly bracket\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.CharGroup CurlyBracket()
```

### Returns

[CharGroup](../../CharGroup/README.md)

## CurlyBracket\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_CurlyBracket_System_Int32_"></a>

\
Appends a pattern that matches left or right curly bracket specified number of times\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup CurlyBracket(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.


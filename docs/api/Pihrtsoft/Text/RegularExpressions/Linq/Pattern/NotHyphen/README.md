# Pattern\.NotHyphen Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotHyphen()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotHyphen) | Appends a pattern that matches a character that is not a hyphen\. |
| [NotHyphen(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotHyphen_System_Int32_) | Appends a pattern that matches a specified number of characters that are not a hyphen\. |

## NotHyphen\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotHyphen"></a>

### Summary

Appends a pattern that matches a character that is not a hyphen\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern NotHyphen()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

## NotHyphen\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotHyphen_System_Int32_"></a>

### Summary

Appends a pattern that matches a specified number of characters that are not a hyphen\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup NotHyphen(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.


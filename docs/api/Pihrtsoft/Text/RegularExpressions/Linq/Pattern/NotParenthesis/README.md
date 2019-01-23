# Pattern\.NotParenthesis Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotParenthesis()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotParenthesis) | Appends a pattern that matches a character that is neither left nor right parenthesis\. |
| [NotParenthesis(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotParenthesis_System_Int32_) | Appends a pattern that matches a character that is neither left nor right parenthesis specified number of times\. |

## NotParenthesis\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotParenthesis"></a>

### Summary

Appends a pattern that matches a character that is neither left nor right parenthesis\.

```csharp
public CharGroup NotParenthesis()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[CharGroup](../../CharGroup/README.md)

## NotParenthesis\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotParenthesis_System_Int32_"></a>

### Summary

Appends a pattern that matches a character that is neither left nor right parenthesis specified number of times\.

```csharp
public QuantifiedGroup NotParenthesis(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

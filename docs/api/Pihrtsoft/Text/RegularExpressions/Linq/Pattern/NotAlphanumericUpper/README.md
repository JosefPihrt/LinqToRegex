# Pattern\.NotAlphanumericUpper Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotAlphanumericUpper()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotAlphanumericUpper) | Appends a pattern that matches a character that is not an upper\-case alphanumeric character\. Alphanumeric character is a latin alphabet upper\-case letter or an arabic digit\. |
| [NotAlphanumericUpper(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotAlphanumericUpper_System_Int32_) | Appends a pattern that matches a character that is not an upper\-case alphanumeric character specified number of times\. Alphanumeric character is a latin alphabet upper\-case letter or an arabic digit\. |

## NotAlphanumericUpper\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotAlphanumericUpper"></a>

### Summary

Appends a pattern that matches a character that is not an upper\-case alphanumeric character\. Alphanumeric character is a latin alphabet upper\-case letter or an arabic digit\.

```csharp
public QuantifiablePattern NotAlphanumericUpper()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

## NotAlphanumericUpper\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotAlphanumericUpper_System_Int32_"></a>

### Summary

Appends a pattern that matches a character that is not an upper\-case alphanumeric character specified number of times\. Alphanumeric character is a latin alphabet upper\-case letter or an arabic digit\.

```csharp
public QuantifiedGroup NotAlphanumericUpper(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

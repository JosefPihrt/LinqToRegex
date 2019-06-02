# Pattern\.CountFrom Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [CountFrom(Int32, Object)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_CountFrom_System_Int32_System_Object_) | Appends a pattern that matches specified pattern at least specified number of times\. |
| [CountFrom(Int32, Object, Object\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_CountFrom_System_Int32_System_Object_System_Object___) | Appends a pattern that matches any one specified pattern at least specified number of times\. |

## CountFrom\(Int32, Object\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_CountFrom_System_Int32_System_Object_"></a>

### Summary

Appends a pattern that matches specified pattern at least specified number of times\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup CountFrom(int minCount, object content)
```

### Parameters

**minCount**

A minimal number of times the pattern must be matched\.

**content**

The content to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**minCount** is less than zero\.

## CountFrom\(Int32, Object, Object\[\]\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_CountFrom_System_Int32_System_Object_System_Object___"></a>

### Summary

Appends a pattern that matches any one specified pattern at least specified number of times\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup CountFrom(int minCount, object first, params object[] others)
```

### Parameters

**minCount**

A minimal number of times the pattern must be matched\.

**first**

First element of a sequence that contains patterns any one of which has to be matched\.

**others**

Other elements of a sequence that contains patterns any one of which has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**first** is `null`\.

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**minCount** is less than zero\.


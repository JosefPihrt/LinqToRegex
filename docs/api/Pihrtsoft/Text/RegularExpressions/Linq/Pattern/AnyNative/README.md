# Pattern\.AnyNative Method

[Home](../../../../../../README.md)

**Containing Type**: [Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [AnyNative()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_AnyNative) | Appends a pattern that matches any character except linefeed \(or any character if the [RegexOptions.Singleline](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regexoptions.singleline) option is applied\)\. |
| [AnyNative(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_AnyNative_System_Int32_) | Appends a pattern that matches any character except linefeed \(or any character if the [RegexOptions.Singleline](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regexoptions.singleline) option is applied\) specified number of times\. |

## AnyNative\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_AnyNative"></a>

\
Appends a pattern that matches any character except linefeed \(or any character if the [RegexOptions.Singleline](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regexoptions.singleline) option is applied\)\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern AnyNative()
```

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

## AnyNative\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_AnyNative_System_Int32_"></a>

\
Appends a pattern that matches any character except linefeed \(or any character if the [RegexOptions.Singleline](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regexoptions.singleline) option is applied\) specified number of times\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup AnyNative(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.


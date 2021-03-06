# Patterns\.EntireInput Method

[Home](../../../../../../README.md)

**Containing Type**: [Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [EntireInput(Object)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_EntireInput_System_Object_) | Returns a pattern that matches a specified content surrounded with the beginning and the end of the string\. |
| [EntireInput(Object\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_EntireInput_System_Object___) | Returns a pattern that matches any one pattern surrounded with the beginning and the end of the string\. |

## EntireInput\(Object\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_EntireInput_System_Object_"></a>

\
Returns a pattern that matches a specified content surrounded with the beginning and the end of the string\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern EntireInput(object content)
```

### Parameters

**content** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)

The content to be matched\.

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

## EntireInput\(Object\[\]\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_EntireInput_System_Object___"></a>

\
Returns a pattern that matches any one pattern surrounded with the beginning and the end of the string\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern EntireInput(params object[] content)
```

### Parameters

**content** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\[\]

An object array that contains zero or more values any one of which has to be matched\.

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.


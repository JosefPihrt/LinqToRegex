# Pattern\.Any Method

[Home](../../../../../../README.md)

**Containing Type**: [Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Any()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Any) | Appends a pattern that matches any character\. |
| [Any(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Any_System_Int32_) | Appends a pattern that matches any character specified number of times\. |
| [Any(Object)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Any_System_Object_) | Appends a noncapturing group with a specified content\. |
| [Any(Object\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Any_System_Object___) | Appends a pattern that matches any one of the patterns specified in the object array\. |

## Any\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Any"></a>

\
Appends a pattern that matches any character\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern Any()
```

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

## Any\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Any_System_Int32_"></a>

\
Appends a pattern that matches any character specified number of times\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup Any(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

## Any\(Object\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Any_System_Object_"></a>

\
Appends a noncapturing group with a specified content\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern Any(object content)
```

### Parameters

**content** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)

The content to be matched\.

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

## Any\(Object\[\]\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Any_System_Object___"></a>

\
Appends a pattern that matches any one of the patterns specified in the object array\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern Any(params object[] content)
```

### Parameters

**content** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\[\]

An object array that contains zero or more patterns any one of which has to be matched\.

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.


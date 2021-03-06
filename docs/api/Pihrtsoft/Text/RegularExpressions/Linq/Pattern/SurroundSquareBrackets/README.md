# Pattern\.SurroundSquareBrackets Method

[Home](../../../../../../README.md)

**Containing Type**: [Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [SurroundSquareBrackets()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundSquareBrackets) | Appends a pattern that matches a text consisting of left and right square bracket, allowing zero or more characters that are not a right square bracket between the brackets\. |
| [SurroundSquareBrackets(Object)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundSquareBrackets_System_Object_) | Appends a pattern that matches specified pattern surrounded with left and right square bracket\. |
| [SurroundSquareBrackets(Object\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundSquareBrackets_System_Object___) | Appends a pattern that matches specified content surrounded with left and right square bracket\. |

## SurroundSquareBrackets\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundSquareBrackets"></a>

\
Appends a pattern that matches a text consisting of left and right square bracket, allowing zero or more characters that are not a right square bracket between the brackets\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.Pattern SurroundSquareBrackets()
```

### Returns

[Pattern](../README.md)

## SurroundSquareBrackets\(Object\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundSquareBrackets_System_Object_"></a>

\
Appends a pattern that matches specified pattern surrounded with left and right square bracket\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.Pattern SurroundSquareBrackets(object content)
```

### Parameters

**content** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)

The content to be matched\.

### Returns

[Pattern](../README.md)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

## SurroundSquareBrackets\(Object\[\]\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_SurroundSquareBrackets_System_Object___"></a>

\
Appends a pattern that matches specified content surrounded with left and right square bracket\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.Pattern SurroundSquareBrackets(params object[] content)
```

### Parameters

**content** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\[\]

An object array that contains zero or more patterns any one of which has to be matched\.

### Returns

[Pattern](../README.md)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.


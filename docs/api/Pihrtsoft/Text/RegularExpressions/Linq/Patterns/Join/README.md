# Patterns\.Join Method

[Home](../../../../../../README.md)

**Containing Type**: [Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Join(Object, Object)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Join_System_Object_System_Object_) | Concatenates the elements in a specified **content** using the specified separator between each element\. |
| [Join(Object, Object\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Join_System_Object_System_Object___) | Concatenates the elements of an object array, using the specified separator between each element\. |

## Join\(Object, Object\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Join_System_Object_System_Object_"></a>

\
Concatenates the elements in a specified **content** using the specified separator between each element\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.Pattern Join(object separator, object content)
```

### Parameters

**separator** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)

The pattern to use as a separator\.

**content** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)

An object that contains the elements to join\.

### Returns

[Pattern](../../Pattern/README.md)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

## Join\(Object, Object\[\]\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Join_System_Object_System_Object___"></a>

\
Concatenates the elements of an object array, using the specified separator between each element\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.Pattern Join(object separator, params object[] content)
```

### Parameters

**separator** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)

The pattern to use as a separator\.

**content** &ensp; [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\[\]

An object array that contains the elements to join\.

### Returns

[Pattern](../../Pattern/README.md)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.


# RegexUtility\.GetEscapeMode Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[RegexUtility](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [GetEscapeMode(Char)](#Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_GetEscapeMode_System_Char_) | Gets a value indicating how a specified character is represented in the regular expression pattern\. |
| [GetEscapeMode(Char, Boolean)](#Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_GetEscapeMode_System_Char_System_Boolean_) | Gets a value indicating how a specified character is represented in the regular expression pattern, specifying whether the character is inside or outside of the character group\. |

## GetEscapeMode\(Char\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_GetEscapeMode_System_Char_"></a>

### Summary

Gets a value indicating how a specified character is represented in the regular expression pattern\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.CharEscapeMode GetEscapeMode(char value)
```

### Parameters

**value** &emsp; System\.[Char](https://docs.microsoft.com/en-us/dotnet/api/system.char)

A Unicode character\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[CharEscapeMode](../../CharEscapeMode/README.md)

## GetEscapeMode\(Char, Boolean\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_GetEscapeMode_System_Char_System_Boolean_"></a>

### Summary

Gets a value indicating how a specified character is represented in the regular expression pattern, specifying whether the character is inside or outside of the character group\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.CharEscapeMode GetEscapeMode(char value, bool inCharGroup)
```

### Parameters

**value** &emsp; System\.[Char](https://docs.microsoft.com/en-us/dotnet/api/system.char)

A Unicode character\.

**inCharGroup** &emsp; System\.[Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean)

Indicates whether the character is inside or outside of the character group\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[CharEscapeMode](../../CharEscapeMode/README.md)


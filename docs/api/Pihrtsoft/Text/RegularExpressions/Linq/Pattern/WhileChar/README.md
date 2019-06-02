# Pattern\.WhileChar Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [WhileChar(AsciiChar)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_WhileChar_Pihrtsoft_Text_RegularExpressions_Linq_AsciiChar_) | Appends a pattern that matches a specified character zero or more times\. |
| [WhileChar(Char)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_WhileChar_System_Char_) | Appends a pattern that matches a specified character zero or more times\. |
| [WhileChar(CharGrouping)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_WhileChar_Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_) | Appends a pattern that matches a specified character zero or more times\. |

## WhileChar\(AsciiChar\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_WhileChar_Pihrtsoft_Text_RegularExpressions_Linq_AsciiChar_"></a>

### Summary

Appends a pattern that matches a specified character zero or more times\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.Pattern WhileChar(Pihrtsoft.Text.RegularExpressions.Linq.AsciiChar value)
```

### Parameters

**value** &emsp; Pihrtsoft\.Text\.RegularExpressions\.Linq\.[AsciiChar](../../AsciiChar/README.md)

An enumerated constant that identifies ASCII character\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

## WhileChar\(Char\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_WhileChar_System_Char_"></a>

### Summary

Appends a pattern that matches a specified character zero or more times\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.Pattern WhileChar(char value)
```

### Parameters

**value** &emsp; System\.[Char](https://docs.microsoft.com/en-us/dotnet/api/system.char)

A Unicode character\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

## WhileChar\(CharGrouping\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_WhileChar_Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_"></a>

### Summary

Appends a pattern that matches a specified character zero or more times\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.Pattern WhileChar(Pihrtsoft.Text.RegularExpressions.Linq.CharGrouping value)
```

### Parameters

**value** &emsp; Pihrtsoft\.Text\.RegularExpressions\.Linq\.[CharGrouping](../../CharGrouping/README.md)

A set of Unicode characters\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**value** is `null`\.


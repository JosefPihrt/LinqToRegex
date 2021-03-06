# RegexUtility\.Escape Method

[Home](../../../../../../README.md)

**Containing Type**: [RegexUtility](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Escape(Char)](#Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_Char_) | Converts a specified character to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents the character as a literal rather than a metacharacter\. The character is considered not to be in the character group\. |
| [Escape(Char, Boolean)](#Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_Char_System_Boolean_) | Converts a specified character to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents the character as a literal rather than a metacharacter\. |
| [Escape(String)](#Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_String_) | Converts a specified text to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents each character as a literal rather than a metacharacter\. The text is considered not to be in the character group\. |
| [Escape(String, Boolean)](#Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_String_System_Boolean_) | Converts a specified input to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents each character as a literal rather than a metacharacter\. |

## Escape\(Char\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_Char_"></a>

\
Converts a specified character to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents the character as a literal rather than a metacharacter\.
The character is considered not to be in the character group\.

```csharp
public static string Escape(char value)
```

### Parameters

**value** &ensp; [Char](https://docs.microsoft.com/en-us/dotnet/api/system.char)

A Unicode character\.

### Returns

[String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

## Escape\(Char, Boolean\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_Char_System_Boolean_"></a>

\
Converts a specified character to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents the character as a literal rather than a metacharacter\.

```csharp
public static string Escape(char value, bool inCharGroup)
```

### Parameters

**value** &ensp; [Char](https://docs.microsoft.com/en-us/dotnet/api/system.char)

A Unicode character\.

**inCharGroup** &ensp; [Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean)

Indicates whether the character is considered to be inside or outside of the character group\.

### Returns

[String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

## Escape\(String\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_String_"></a>

\
Converts a specified text to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents each character as a literal rather than a metacharacter\.
The text is considered not to be in the character group\.

```csharp
public static string Escape(string input)
```

### Parameters

**input** &ensp; [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

The text to be converted\.

### Returns

[String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**input** is `null`\.

## Escape\(String, Boolean\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_RegexUtility_Escape_System_String_System_Boolean_"></a>

\
Converts a specified input to the [String](https://docs.microsoft.com/en-us/dotnet/api/system.string) object that represents each character as a literal rather than a metacharacter\.

```csharp
public static string Escape(string input, bool inCharGroup)
```

### Parameters

**input** &ensp; [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

The text to be converted\.

**inCharGroup** &ensp; [Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean)

Indicates whether the text is considered to be inside or outside of the character group\.

### Returns

[String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

### Exceptions

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**input** is `null`\.


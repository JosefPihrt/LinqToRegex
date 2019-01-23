# Pattern\.BitwiseOr Operator

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Operator | Summary |
| -------- | ------- |
| [BitwiseOr(Char, Pattern)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_op_BitwiseOr_System_Char_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_) | Creates a pattern that matches any one of the specified elements\. |
| [BitwiseOr(CharGrouping, Pattern)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_op_BitwiseOr_Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_) | Creates a pattern that matches any one of the specified elements\. |
| [BitwiseOr(Pattern, Char)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_op_BitwiseOr_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_System_Char_) | Creates a pattern that matches any one of the specified elements\. |
| [BitwiseOr(Pattern, CharGrouping)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_op_BitwiseOr_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_) | Creates a pattern that matches any one of the specified elements\. |
| [BitwiseOr(Pattern, Pattern)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_op_BitwiseOr_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_) | Creates a pattern that matches any one of the specified elements\. |
| [BitwiseOr(Pattern, String)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_op_BitwiseOr_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_System_String_) | Creates a pattern that matches any one of the specified elements\. |
| [BitwiseOr(String, Pattern)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_op_BitwiseOr_System_String_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_) | Creates a pattern that matches any one of the specified elements\. |

## BitwiseOr\(Char, Pattern\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_op_BitwiseOr_System_Char_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_"></a>

### Summary

Creates a pattern that matches any one of the specified elements\.

```csharp
public static QuantifiablePattern operator |(char left, Pattern right)
```

### Parameters

**left**

The first element to match\.

**right**

The second element to match\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**right** is `null`\.

## BitwiseOr\(CharGrouping, Pattern\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_op_BitwiseOr_Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_"></a>

### Summary

Creates a pattern that matches any one of the specified elements\.

```csharp
public static QuantifiablePattern operator |(CharGrouping left, Pattern right)
```

### Parameters

**left**

The first element to match\.

**right**

The second element to match\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**left** or **right** is `null`\.

## BitwiseOr\(Pattern, Char\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_op_BitwiseOr_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_System_Char_"></a>

### Summary

Creates a pattern that matches any one of the specified elements\.

```csharp
public static QuantifiablePattern operator |(Pattern left, char right)
```

### Parameters

**left**

The first element to match\.

**right**

The second element to match\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**left** is `null`\.

## BitwiseOr\(Pattern, CharGrouping\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_op_BitwiseOr_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_"></a>

### Summary

Creates a pattern that matches any one of the specified elements\.

```csharp
public static QuantifiablePattern operator |(Pattern left, CharGrouping right)
```

### Parameters

**left**

The first element to match\.

**right**

The second element to match\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**left** or **right** is `null`\.

## BitwiseOr\(Pattern, Pattern\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_op_BitwiseOr_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_"></a>

### Summary

Creates a pattern that matches any one of the specified elements\.

```csharp
public static QuantifiablePattern operator |(Pattern left, Pattern right)
```

### Parameters

**left**

The first element to match\.

**right**

The second element to match\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**left** or **right** is `null`\.

## BitwiseOr\(Pattern, String\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_op_BitwiseOr_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_System_String_"></a>

### Summary

Creates a pattern that matches any one of the specified elements\.

```csharp
public static QuantifiablePattern operator |(Pattern left, string right)
```

### Parameters

**left**

The first element to match\.

**right**

The second element to match\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**left** or **right** is `null`\.

## BitwiseOr\(String, Pattern\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_op_BitwiseOr_System_String_Pihrtsoft_Text_RegularExpressions_Linq_Pattern_"></a>

### Summary

Creates a pattern that matches any one of the specified elements\.

```csharp
public static QuantifiablePattern operator |(string left, Pattern right)
```

### Parameters

**left**

The first element to match\.

**right**

The second element to match\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**left** or **right** is `null`\.

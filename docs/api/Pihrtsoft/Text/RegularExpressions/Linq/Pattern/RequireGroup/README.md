# Pattern\.RequireGroup Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [RequireGroup(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_RequireGroup_System_Int32_) | Appends a pattern that requires previously defined group with a specified number to be matched\. Otherwise, a match will fail\. |
| [RequireGroup(String)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_RequireGroup_System_String_) | Appends a pattern that requires previously defined group with a specified name to be matched\. Otherwise, a match will fail\. |

## RequireGroup\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_RequireGroup_System_Int32_"></a>

### Summary

Appends a pattern that requires previously defined group with a specified number to be matched\. Otherwise, a match will fail\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.Pattern RequireGroup(int groupNumber)
```

### Parameters

**groupNumber**

A number of the group\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**groupNumber** is less than zero\.

## RequireGroup\(String\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_RequireGroup_System_String_"></a>

### Summary

Appends a pattern that requires previously defined group with a specified name to be matched\. Otherwise, a match will fail\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.Pattern RequireGroup(string groupName)
```

### Parameters

**groupName**

A name of the group\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

### Exceptions

System\.[ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentexception)

**groupName** is not a valid regex group name\.

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**groupName** is `null`\.


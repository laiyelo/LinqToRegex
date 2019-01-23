# Patterns\.NotLeftAngleBracket Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotLeftAngleBracket()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotLeftAngleBracket) | Returns a pattern that matches a character that is not a left angle bracket \(less\-than sign\)\. |
| [NotLeftAngleBracket(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotLeftAngleBracket_System_Int32_) | Returns a pattern that matches a specified number of characters that are not a left angle bracket \(less\-than sign\)\. |

## NotLeftAngleBracket\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotLeftAngleBracket"></a>

### Summary

Returns a pattern that matches a character that is not a left angle bracket \(less\-than sign\)\.

```csharp
public static QuantifiablePattern NotLeftAngleBracket()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

## NotLeftAngleBracket\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_NotLeftAngleBracket_System_Int32_"></a>

### Summary

Returns a pattern that matches a specified number of characters that are not a left angle bracket \(less\-than sign\)\.

```csharp
public static QuantifiedGroup NotLeftAngleBracket(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

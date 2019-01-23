# Patterns\.LatinLetterUpper Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [LatinLetterUpper()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_LatinLetterUpper) | Returns a pattern that matches a latin alphabet upper\-case letter\. |
| [LatinLetterUpper(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_LatinLetterUpper_System_Int32_) | Returns a pattern that matches a specified number of latin alphabet upper\-case letters\. |

## LatinLetterUpper\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_LatinLetterUpper"></a>

### Summary

Returns a pattern that matches a latin alphabet upper\-case letter\.

```csharp
public static QuantifiablePattern LatinLetterUpper()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

## LatinLetterUpper\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_LatinLetterUpper_System_Int32_"></a>

### Summary

Returns a pattern that matches a specified number of latin alphabet upper\-case letters\.

```csharp
public static QuantifiedGroup LatinLetterUpper(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

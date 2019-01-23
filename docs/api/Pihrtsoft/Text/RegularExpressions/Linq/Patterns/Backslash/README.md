# Patterns\.Backslash Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Backslash()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Backslash) | Returns a pattern that matches a backslash\. |
| [Backslash(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Backslash_System_Int32_) | Returns a pattern that matches a specified number of backslashes\. |

## Backslash\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Backslash"></a>

### Summary

Returns a pattern that matches a backslash\.

```csharp
public static CharPattern Backslash()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[CharPattern](../../CharPattern/README.md)

## Backslash\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Backslash_System_Int32_"></a>

### Summary

Returns a pattern that matches a specified number of backslashes\.

```csharp
public static QuantifiedGroup Backslash(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

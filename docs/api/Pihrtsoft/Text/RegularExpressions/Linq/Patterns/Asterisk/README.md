# Patterns\.Asterisk Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Asterisk()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Asterisk) | Returns a pattern that matches an asterisk\. |
| [Asterisk(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Asterisk_System_Int32_) | Returns a pattern that matches a specified number of asterisks\. |

## Asterisk\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Asterisk"></a>

### Summary

Returns a pattern that matches an asterisk\.

```csharp
public static CharPattern Asterisk()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[CharPattern](../../CharPattern/README.md)

## Asterisk\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_Asterisk_System_Int32_"></a>

### Summary

Returns a pattern that matches a specified number of asterisks\.

```csharp
public static QuantifiedGroup Asterisk(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

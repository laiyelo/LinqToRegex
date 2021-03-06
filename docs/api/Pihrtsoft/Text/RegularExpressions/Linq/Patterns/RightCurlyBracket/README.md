# Patterns\.RightCurlyBracket Method

[Home](../../../../../../README.md)

**Containing Type**: [Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [RightCurlyBracket()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_RightCurlyBracket) | Returns a pattern that matches a right curly bracket\. |
| [RightCurlyBracket(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_RightCurlyBracket_System_Int32_) | Returns a pattern that matches a specified number of right curly brackets\. |

## RightCurlyBracket\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_RightCurlyBracket"></a>

\
Returns a pattern that matches a right curly bracket\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.CharPattern RightCurlyBracket()
```

### Returns

[CharPattern](../../CharPattern/README.md)

## RightCurlyBracket\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_RightCurlyBracket_System_Int32_"></a>

\
Returns a pattern that matches a specified number of right curly brackets\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup RightCurlyBracket(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.


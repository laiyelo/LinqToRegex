# Pattern\.NotDot Method

[Home](../../../../../../README.md)

**Containing Type**: [Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [NotDot()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotDot) | Appends a pattern that matches a character that is not a dot\. |
| [NotDot(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotDot_System_Int32_) | Appends a pattern that matches a specified number of characters that are not a dot\. |

## NotDot\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotDot"></a>

\
Appends a pattern that matches a character that is not a dot\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern NotDot()
```

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

## NotDot\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_NotDot_System_Int32_"></a>

\
Appends a pattern that matches a specified number of characters that are not a dot\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup NotDot(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.


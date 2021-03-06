# Pattern\.Ampersand Method

[Home](../../../../../../README.md)

**Containing Type**: [Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Ampersand()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Ampersand) | Appends a pattern that matches an ampersand\. |
| [Ampersand(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Ampersand_System_Int32_) | Appends a pattern that matches a specified number of ampersands\. |

## Ampersand\(\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Ampersand"></a>

\
Appends a pattern that matches an ampersand\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern Ampersand()
```

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

## Ampersand\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Ampersand_System_Int32_"></a>

\
Appends a pattern that matches a specified number of ampersands\.

```csharp
public Pihrtsoft.Text.RegularExpressions.Linq.QuantifiedGroup Ampersand(int exactCount)
```

### Parameters

**exactCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of times a character has to be matched\.

### Returns

[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.


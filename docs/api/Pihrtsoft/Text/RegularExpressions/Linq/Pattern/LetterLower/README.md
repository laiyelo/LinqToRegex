# Pattern\.LetterLower Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [LetterLower()](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_LetterLower) | Appends a pattern that matches a character from [GeneralCategory.LetterLowercase](../../GeneralCategory/LetterLowercase/README.md)\. |
| [LetterLower(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_LetterLower_System_Int32_) | Appends a pattern that matches a specified number of letters from [GeneralCategory.LetterLowercase](../../GeneralCategory/LetterLowercase/README.md)\. |

## LetterLower\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_LetterLower"></a>

### Summary

Appends a pattern that matches a character from [GeneralCategory.LetterLowercase](../../GeneralCategory/LetterLowercase/README.md)\.

```csharp
public QuantifiablePattern LetterLower()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

## LetterLower\(Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_LetterLower_System_Int32_"></a>

### Summary

Appends a pattern that matches a specified number of letters from [GeneralCategory.LetterLowercase](../../GeneralCategory/LetterLowercase/README.md)\.

```csharp
public QuantifiedGroup LetterLower(int exactCount)
```

### Parameters

**exactCount**

A number of times a character has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**exactCount** is less than zero\.

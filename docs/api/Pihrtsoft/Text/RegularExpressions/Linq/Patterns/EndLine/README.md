# Patterns\.EndLine Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [EndLine()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_EndLine) | Returns a pattern that is matched at the end of the string or line\. End of line is defined as the position before a linefeed\. |
| [EndLine(Boolean)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_EndLine_System_Boolean_) | Returns a pattern that is matched \(before carriage return\) at the end of the string or line\. End of line is defined as the position before a linefeed\. |

## EndLine\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_EndLine"></a>

### Summary

Returns a pattern that is matched at the end of the string or line\. End of line is defined as the position before a linefeed\.

```csharp
public static QuantifiablePattern EndLine()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiablePattern](../../QuantifiablePattern/README.md)

## EndLine\(Boolean\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_EndLine_System_Boolean_"></a>

### Summary

Returns a pattern that is matched \(before carriage return\) at the end of the string or line\. End of line is defined as the position before a linefeed\.

```csharp
public static Pattern EndLine(bool beforeCarriageReturn)
```

### Parameters

**beforeCarriageReturn**

Indicates whether a position of the match should be before a carriage return if present and not already consumed by regex engine

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../../Pattern/README.md)

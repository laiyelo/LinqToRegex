# Patterns\.GroupReference Method

[Home](../../../../../../README.md)

**Containing Type**: [Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [GroupReference(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_GroupReference_System_Int32_) | Returns a pattern that matches previously defined numbered group\. |
| [GroupReference(String)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_GroupReference_System_String_) | Returns a pattern that matches previously defined named group\. |

## GroupReference\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_GroupReference_System_Int32_"></a>

\
Returns a pattern that matches previously defined numbered group\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern GroupReference(int groupNumber)
```

### Parameters

**groupNumber** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A number of the group\.

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**groupNumber** is less than zero\.

## GroupReference\(String\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_GroupReference_System_String_"></a>

\
Returns a pattern that matches previously defined named group\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.QuantifiablePattern GroupReference(string groupName)
```

### Parameters

**groupName** &ensp; [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

A name of the group\.

### Returns

[QuantifiablePattern](../../QuantifiablePattern/README.md)

### Exceptions

[ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentexception)

**groupName** is not a valid regex group name\.

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**groupName** is `null`\.


# PatternBuilder\.AppendCountFrom Method

[Home](../../../../../../README.md)

**Containing Type**: [PatternBuilder](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [AppendCountFrom(Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_PatternBuilder_AppendCountFrom_System_Int32_) | Appends a quantifier that matches previous element at least specified number of times\. |
| [AppendCountFrom(Int32, Boolean)](#Pihrtsoft_Text_RegularExpressions_Linq_PatternBuilder_AppendCountFrom_System_Int32_System_Boolean_) | Appends a quantifier that matches previous element at least specified number of times\. |

## AppendCountFrom\(Int32\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_PatternBuilder_AppendCountFrom_System_Int32_"></a>

\
Appends a quantifier that matches previous element at least specified number of times\.

```csharp
public void AppendCountFrom(int minCount)
```

### Parameters

**minCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A minimal number of times the pattern must be matched\.

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**minCount** is less than zero\.

## AppendCountFrom\(Int32, Boolean\) <a id="Pihrtsoft_Text_RegularExpressions_Linq_PatternBuilder_AppendCountFrom_System_Int32_System_Boolean_"></a>

\
Appends a quantifier that matches previous element at least specified number of times\.

```csharp
public void AppendCountFrom(int minCount, bool lazy)
```

### Parameters

**minCount** &ensp; [Int32](https://docs.microsoft.com/en-us/dotnet/api/system.int32)

A minimal number of times the pattern must be matched\.

**lazy** &ensp; [Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean)

Indicates whether the quantifier will be greedy or lazy\.

### Exceptions

[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**minCount** is less than zero\.


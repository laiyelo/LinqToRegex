# CharGrouping\.Explicit Operator

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[CharGrouping](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Operator | Summary |
| -------- | ------- |
| [Explicit(Char to CharGrouping)](#Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_op_Explicit_System_Char__Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping) | Converts specified character to an instance of the [CharGrouping](../README.md) class\. |
| [Explicit(String to CharGrouping)](#Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_op_Explicit_System_String__Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping) | Converts specified characters to an instance of the [CharGrouping](../README.md) class\. |

## Explicit\(Char to CharGrouping\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_op_Explicit_System_Char__Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping"></a>

### Summary

Converts specified character to an instance of the [CharGrouping](../README.md) class\.

```csharp
public static explicit operator CharGrouping(char value)
```

### Parameters

**value**

A Unicode character\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[CharGrouping](../README.md)

## Explicit\(String to CharGrouping\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_op_Explicit_System_String__Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping"></a>

### Summary

Converts specified characters to an instance of the [CharGrouping](../README.md) class\.

```csharp
public static explicit operator CharGrouping(string characters)
```

### Parameters

**characters**

A set of Unicode characters\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[CharGrouping](../README.md)

### Exceptions

System\.[ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentexception)

**characters** length is equal to zero\.

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**characters** is `null`\.

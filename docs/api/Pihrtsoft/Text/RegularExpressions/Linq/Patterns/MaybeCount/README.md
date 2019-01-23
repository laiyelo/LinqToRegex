# Patterns\.MaybeCount Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [MaybeCount(Int32, Object)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_MaybeCount_System_Int32_System_Object_) | Returns a pattern that matches specified pattern at most specified number of times\. |
| [MaybeCount(Int32, Object, Object\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_MaybeCount_System_Int32_System_Object_System_Object___) | Returns a pattern that matches any one specified pattern at most specified number of times\. |

## MaybeCount\(Int32, Object\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_MaybeCount_System_Int32_System_Object_"></a>

### Summary

Returns a pattern that matches specified pattern at most specified number of times\.

```csharp
public static QuantifiedGroup MaybeCount(int maxCount, object content)
```

### Parameters

**maxCount**

A maximum number of times the pattern can be matched\.

**content**

The content to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**maxCount** is less than zero\.

## MaybeCount\(Int32, Object, Object\[\]\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_MaybeCount_System_Int32_System_Object_System_Object___"></a>

### Summary

Returns a pattern that matches any one specified pattern at most specified number of times\.

```csharp
public static QuantifiedGroup MaybeCount(int maxCount, object first, params object[] others)
```

### Parameters

**maxCount**

A maximum number of times the pattern can be matched\.

**first**

First element of a sequence that contains patterns any one of which has to be matched\.

**others**

Other elements of a sequence that contains patterns any one of which has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**first** is `null`\.

System\.[ArgumentOutOfRangeException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentoutofrangeexception)

**maxCount** is less than zero\.

# Patterns\.SurroundCurlyBrackets Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [SurroundCurlyBrackets()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_SurroundCurlyBrackets) | Returns a pattern that matches a text consisting of left and right curly bracket, allowing zero or more characters that are not a right curly bracket between the brackets\. |
| [SurroundCurlyBrackets(Object)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_SurroundCurlyBrackets_System_Object_) | Returns a pattern that matches specified pattern surrounded with left and right curly bracket\. |
| [SurroundCurlyBrackets(Object\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_SurroundCurlyBrackets_System_Object___) | Returns a pattern that matches specified content surrounded with left and right curly bracket\. |

## SurroundCurlyBrackets\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_SurroundCurlyBrackets"></a>

### Summary

Returns a pattern that matches a text consisting of left and right curly bracket, allowing zero or more characters that are not a right curly bracket between the brackets\.

```csharp
public static Pattern SurroundCurlyBrackets()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../../Pattern/README.md)

## SurroundCurlyBrackets\(Object\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_SurroundCurlyBrackets_System_Object_"></a>

### Summary

Returns a pattern that matches specified pattern surrounded with left and right curly bracket\.

```csharp
public static Pattern SurroundCurlyBrackets(object content)
```

### Parameters

**content**

The content to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../../Pattern/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

## SurroundCurlyBrackets\(Object\[\]\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_SurroundCurlyBrackets_System_Object___"></a>

### Summary

Returns a pattern that matches specified content surrounded with left and right curly bracket\.

```csharp
public static Pattern SurroundCurlyBrackets(params object[] content)
```

### Parameters

**content**

An object array that contains zero or more patterns any one of which has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../../Pattern/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

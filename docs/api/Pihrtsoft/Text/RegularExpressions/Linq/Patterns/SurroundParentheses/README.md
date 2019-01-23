# Patterns\.SurroundParentheses Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [SurroundParentheses()](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_SurroundParentheses) | Returns a pattern that matches a text consisting of a left parenthesis and a right parenthesis, allowing zero or more characters that are not a right parenthesis between the parentheses\. |
| [SurroundParentheses(Object)](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_SurroundParentheses_System_Object_) | Returns a pattern that matches specified pattern surrounded with left and right parenthesis\. |
| [SurroundParentheses(Object\[\])](#Pihrtsoft_Text_RegularExpressions_Linq_Patterns_SurroundParentheses_System_Object___) | Returns a pattern that matches specified content surrounded with left and right parenthesis\. |

## SurroundParentheses\(\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_SurroundParentheses"></a>

### Summary

Returns a pattern that matches a text consisting of a left parenthesis and a right parenthesis, allowing zero or more characters that are not a right parenthesis between the parentheses\.

```csharp
public static Pattern SurroundParentheses()
```

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../../Pattern/README.md)

## SurroundParentheses\(Object\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_SurroundParentheses_System_Object_"></a>

### Summary

Returns a pattern that matches specified pattern surrounded with left and right parenthesis\.

```csharp
public static Pattern SurroundParentheses(object content)
```

### Parameters

**content**

The content to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../../Pattern/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

## SurroundParentheses\(Object\[\]\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Patterns_SurroundParentheses_System_Object___"></a>

### Summary

Returns a pattern that matches specified content surrounded with left and right parenthesis\.

```csharp
public static Pattern SurroundParentheses(params object[] content)
```

### Parameters

**content**

An object array that contains zero or more patterns any one of which has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../../Pattern/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**content** is `null`\.

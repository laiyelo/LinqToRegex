# Patterns\.BalanceParentheses\(String\) Method

[Home](../../../../../../README.md)

**Containing Type**: [Patterns](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

\
Returns a pattern that matches one or many left parenthesis balanced with one or many right parenthesis\.
Between the characters can be zero or many characters that are neither left nor right parenthesis\.

```csharp
public static Pihrtsoft.Text.RegularExpressions.Linq.Pattern BalanceParentheses(string groupName)
```

### Parameters

**groupName** &ensp; [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)

A name of the group that contains balanced content between left and right parenthesis\.

### Returns

[Pattern](../../Pattern/README.md)

### Exceptions

[ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentexception)

**groupName** is not a valid regex group name\.

[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**groupName** is `null`\.


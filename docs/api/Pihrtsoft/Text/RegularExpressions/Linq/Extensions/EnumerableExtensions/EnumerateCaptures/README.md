# EnumerableExtensions\.EnumerateCaptures Method

[Home](../../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.Extensions\.[EnumerableExtensions](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [EnumerateCaptures(IEnumerable\<Group>)](#Pihrtsoft_Text_RegularExpressions_Linq_Extensions_EnumerableExtensions_EnumerateCaptures_System_Collections_Generic_IEnumerable_System_Text_RegularExpressions_Group__) | Returns an enumerable collection of captures\. |
| [EnumerateCaptures(IEnumerable\<Match>)](#Pihrtsoft_Text_RegularExpressions_Linq_Extensions_EnumerableExtensions_EnumerateCaptures_System_Collections_Generic_IEnumerable_System_Text_RegularExpressions_Match__) | Returns an enumerable collection of captures\. |
| [EnumerateCaptures(IEnumerable\<Match>, Int32)](#Pihrtsoft_Text_RegularExpressions_Linq_Extensions_EnumerableExtensions_EnumerateCaptures_System_Collections_Generic_IEnumerable_System_Text_RegularExpressions_Match__System_Int32_) | Returns an enumerable collection of captures from groups that have a specified number\. |
| [EnumerateCaptures(IEnumerable\<Match>, String)](#Pihrtsoft_Text_RegularExpressions_Linq_Extensions_EnumerableExtensions_EnumerateCaptures_System_Collections_Generic_IEnumerable_System_Text_RegularExpressions_Match__System_String_) | Returns an enumerable collection of captures from groups thas have a specified name\. |

## EnumerateCaptures\(IEnumerable\<Group>\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Extensions_EnumerableExtensions_EnumerateCaptures_System_Collections_Generic_IEnumerable_System_Text_RegularExpressions_Group__"></a>

### Summary

Returns an enumerable collection of captures\.

```csharp
public static IEnumerable<Capture> EnumerateCaptures(this IEnumerable<Group> groups)
```

### Parameters

**groups**

The sequence to enumerate\.

### Returns

System\.Collections\.Generic\.[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<[Capture](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.capture)>

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**groups** is `null`\.

## EnumerateCaptures\(IEnumerable\<Match>\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Extensions_EnumerableExtensions_EnumerateCaptures_System_Collections_Generic_IEnumerable_System_Text_RegularExpressions_Match__"></a>

### Summary

Returns an enumerable collection of captures\.

```csharp
public static IEnumerable<Capture> EnumerateCaptures(this IEnumerable<Match> matches)
```

### Parameters

**matches**

The sequence to enumerate\.

### Returns

System\.Collections\.Generic\.[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<[Capture](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.capture)>

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**matches** is `null`\.

## EnumerateCaptures\(IEnumerable\<Match>, Int32\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Extensions_EnumerableExtensions_EnumerateCaptures_System_Collections_Generic_IEnumerable_System_Text_RegularExpressions_Match__System_Int32_"></a>

### Summary

Returns an enumerable collection of captures from groups that have a specified number\.

```csharp
public static IEnumerable<Capture> EnumerateCaptures(this IEnumerable<Match> matches, int groupNumber)
```

### Parameters

**matches**

The sequence to enumerate\.

**groupNumber**

A number of the group\.

### Returns

System\.Collections\.Generic\.[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<[Capture](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.capture)>

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**matches** is `null`\.

## EnumerateCaptures\(IEnumerable\<Match>, String\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Extensions_EnumerableExtensions_EnumerateCaptures_System_Collections_Generic_IEnumerable_System_Text_RegularExpressions_Match__System_String_"></a>

### Summary

Returns an enumerable collection of captures from groups thas have a specified name\.

```csharp
public static IEnumerable<Capture> EnumerateCaptures(this IEnumerable<Match> matches, string groupName)
```

### Parameters

**matches**

The sequence to enumerate\.

**groupName**

A name of the group\.

### Returns

System\.Collections\.Generic\.[IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1)\<[Capture](https://docs.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.capture)>

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**matches** or **groupName** is `null`\.

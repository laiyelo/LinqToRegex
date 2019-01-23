# Pattern\.Characters Method

[Home](../../../../../../README.md)

**Containing Type**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.[Pattern](../README.md)

**Assembly**: Pihrtsoft\.Text\.RegularExpressions\.Linq\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Characters(AsciiChar)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Characters_Pihrtsoft_Text_RegularExpressions_Linq_AsciiChar_) | Appends a pattern that matches a specified character one or more times\. |
| [Characters(GeneralCategory)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Characters_Pihrtsoft_Text_RegularExpressions_Linq_GeneralCategory_) | Appends a pattern that matches one or more characters from a specified Unicode category\. |
| [Characters(Char)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Characters_System_Char_) | Appends a pattern that matches a specified character one or more times\. |
| [Characters(CharGrouping)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Characters_Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_) | Appends a pattern that matches one or more characters from a specified [CharGrouping](../../CharGrouping/README.md)\. |
| [Characters(NamedBlock)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Characters_Pihrtsoft_Text_RegularExpressions_Linq_NamedBlock_) | Appends a pattern that matches one or more characters from a specified Unicode block\. |
| [Characters(String)](#Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Characters_System_String_) | Appends a pattern that matches one or more characters from a specified [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)\. |

## Characters\(AsciiChar\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Characters_Pihrtsoft_Text_RegularExpressions_Linq_AsciiChar_"></a>

### Summary

Appends a pattern that matches a specified character one or more times\.

```csharp
public QuantifiedGroup Characters(AsciiChar value)
```

### Parameters

**value**

An enumerated constant that identifies ASCII character\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

## Characters\(GeneralCategory\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Characters_Pihrtsoft_Text_RegularExpressions_Linq_GeneralCategory_"></a>

### Summary

Appends a pattern that matches one or more characters from a specified Unicode category\.

```csharp
public QuantifiedGroup Characters(GeneralCategory category)
```

### Parameters

**category**

An enumerated constant that identifies Unicode category\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

## Characters\(Char\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Characters_System_Char_"></a>

### Summary

Appends a pattern that matches a specified character one or more times\.

```csharp
public QuantifiedGroup Characters(char value)
```

### Parameters

**value**

A Unicode character\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

## Characters\(CharGrouping\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Characters_Pihrtsoft_Text_RegularExpressions_Linq_CharGrouping_"></a>

### Summary

Appends a pattern that matches one or more characters from a specified [CharGrouping](../../CharGrouping/README.md)\.

```csharp
public QuantifiedGroup Characters(CharGrouping value)
```

### Parameters

**value**

A content of a character group\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**value** is `null`\.

## Characters\(NamedBlock\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Characters_Pihrtsoft_Text_RegularExpressions_Linq_NamedBlock_"></a>

### Summary

Appends a pattern that matches one or more characters from a specified Unicode block\.

```csharp
public QuantifiedGroup Characters(NamedBlock block)
```

### Parameters

**block**

An enumerated constant that identifies Unicode block\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

## Characters\(String\) <a name="Pihrtsoft_Text_RegularExpressions_Linq_Pattern_Characters_System_String_"></a>

### Summary

Appends a pattern that matches one or more characters from a specified [String](https://docs.microsoft.com/en-us/dotnet/api/system.string)\.

```csharp
public QuantifiedGroup Characters(string value)
```

### Parameters

**value**

A set of characters any one of which has to be matched\.

### Returns

Pihrtsoft\.Text\.RegularExpressions\.Linq\.[QuantifiedGroup](../../QuantifiedGroup/README.md)

### Exceptions

System\.[ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentexception)

**value** length is equal to zero\.

System\.[ArgumentNullException](https://docs.microsoft.com/en-us/dotnet/api/system.argumentnullexception)

**value** is `null`\.

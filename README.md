# Formulator.NET

Formulator is an Excel-like formula evaluation engine for .NET

## Features
* Number, String and Date calculations
* Logical comparisons, with IF(), AND() and OR()
* Variables
* 75+ includes functions

## Example
```csharp
var formulator = new Formulator(); 
formulator.Variable("foo","bar");
var result = formulator.Evaluate(@"IF(AND(foo = ""bar"", Date.Now()> ""1 JAN 2020""),String.ToUpper(foo),""foobar"")");
//result: BAR
```

## Live Demo
<https://www.formulator.net>

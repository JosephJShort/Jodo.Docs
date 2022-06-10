# TwoDimensionalExtensions.Translate(*T*, *N*) Method (*T*, ValueTuple(*N*, *N*))
 _**\[This is preliminary documentation and is subject to change.\]**_

\[Missing <summary> documentation for "M:Jodo.Extensions.Geometry.TwoDimensionalExtensions.Translate``2(``0,System.ValueTuple{``1,``1})"\]

**Namespace:**&nbsp;<a href="N_Jodo_Extensions_Geometry">Jodo.Extensions.Geometry</a><br />**Assembly:**&nbsp;Jodo.Extensions.Geometry (in Jodo.Extensions.Geometry.dll) Version: 1.1.0.0

## Syntax

**C#**<br />
``` C#
public static T Translate<T, N>(
	this T value,
	(N , N ) delta
)
where T : struct, new(), ITwoDimensional<T, N>
where N : struct, new(), INumeric<N>

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: *T*<br />\[Missing <param name="value"/> documentation for "M:Jodo.Extensions.Geometry.TwoDimensionalExtensions.Translate``2(``0,System.ValueTuple{``1,``1})"\]</dd><dt>delta</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.valuetuple-2" target="_blank" rel="noopener noreferrer">System.ValueTuple</a>(*N*, *N*)<br />\[Missing <param name="delta"/> documentation for "M:Jodo.Extensions.Geometry.TwoDimensionalExtensions.Translate``2(``0,System.ValueTuple{``1,``1})"\]</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:Jodo.Extensions.Geometry.TwoDimensionalExtensions.Translate``2(``0,System.ValueTuple{``1,``1})"\]</dd><dt>N</dt><dd>\[Missing <typeparam name="N"/> documentation for "M:Jodo.Extensions.Geometry.TwoDimensionalExtensions.Translate``2(``0,System.ValueTuple{``1,``1})"\]</dd></dl>

#### Return Value
Type: *T*<br />\[Missing <returns> documentation for "M:Jodo.Extensions.Geometry.TwoDimensionalExtensions.Translate``2(``0,System.ValueTuple{``1,``1})"\]

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_Jodo_Extensions_Geometry_TwoDimensionalExtensions">TwoDimensionalExtensions Class</a><br /><a href="Overload_Jodo_Extensions_Geometry_TwoDimensionalExtensions_Translate">Translate Overload</a><br /><a href="N_Jodo_Extensions_Geometry">Jodo.Extensions.Geometry Namespace</a><br />
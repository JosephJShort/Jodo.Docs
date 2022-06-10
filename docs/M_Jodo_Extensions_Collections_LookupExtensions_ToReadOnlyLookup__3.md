# LookupExtensions.ToReadOnlyLookup(*TSource*, *TKey*, *TElement*) Method (IEnumerable(*TSource*), Func(*TSource*, *TKey*), Func(*TSource*, *TElement*))
 _**\[This is preliminary documentation and is subject to change.\]**_

\[Missing <summary> documentation for "M:Jodo.Extensions.Collections.LookupExtensions.ToReadOnlyLookup``3(System.Collections.Generic.IEnumerable{``0},System.Func{``0,``1},System.Func{``0,``2})"\]

**Namespace:**&nbsp;<a href="N_Jodo_Extensions_Collections">Jodo.Extensions.Collections</a><br />**Assembly:**&nbsp;Jodo.Extensions.Collections (in Jodo.Extensions.Collections.dll) Version: 1.1.0.0

## Syntax

**C#**<br />
``` C#
public static IReadOnlyLookup<TKey, TElement> ToReadOnlyLookup<TSource, TKey, TElement>(
	this IEnumerable<TSource> source,
	Func<TSource, TKey> keySelector,
	Func<TSource, TElement> elementSelector
)

```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ienumerable-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IEnumerable</a>(*TSource*)<br />\[Missing <param name="source"/> documentation for "M:Jodo.Extensions.Collections.LookupExtensions.ToReadOnlyLookup``3(System.Collections.Generic.IEnumerable{``0},System.Func{``0,``1},System.Func{``0,``2})"\]</dd><dt>keySelector</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.func-2" target="_blank" rel="noopener noreferrer">System.Func</a>(*TSource*, *TKey*)<br />\[Missing <param name="keySelector"/> documentation for "M:Jodo.Extensions.Collections.LookupExtensions.ToReadOnlyLookup``3(System.Collections.Generic.IEnumerable{``0},System.Func{``0,``1},System.Func{``0,``2})"\]</dd><dt>elementSelector</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.func-2" target="_blank" rel="noopener noreferrer">System.Func</a>(*TSource*, *TElement*)<br />\[Missing <param name="elementSelector"/> documentation for "M:Jodo.Extensions.Collections.LookupExtensions.ToReadOnlyLookup``3(System.Collections.Generic.IEnumerable{``0},System.Func{``0,``1},System.Func{``0,``2})"\]</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>TSource</dt><dd>\[Missing <typeparam name="TSource"/> documentation for "M:Jodo.Extensions.Collections.LookupExtensions.ToReadOnlyLookup``3(System.Collections.Generic.IEnumerable{``0},System.Func{``0,``1},System.Func{``0,``2})"\]</dd><dt>TKey</dt><dd>\[Missing <typeparam name="TKey"/> documentation for "M:Jodo.Extensions.Collections.LookupExtensions.ToReadOnlyLookup``3(System.Collections.Generic.IEnumerable{``0},System.Func{``0,``1},System.Func{``0,``2})"\]</dd><dt>TElement</dt><dd>\[Missing <typeparam name="TElement"/> documentation for "M:Jodo.Extensions.Collections.LookupExtensions.ToReadOnlyLookup``3(System.Collections.Generic.IEnumerable{``0},System.Func{``0,``1},System.Func{``0,``2})"\]</dd></dl>

#### Return Value
Type: <a href="T_Jodo_Extensions_Collections_IReadOnlyLookup_2">IReadOnlyLookup</a>(*TKey*, *TElement*)<br />\[Missing <returns> documentation for "M:Jodo.Extensions.Collections.LookupExtensions.ToReadOnlyLookup``3(System.Collections.Generic.IEnumerable{``0},System.Func{``0,``1},System.Func{``0,``2})"\]

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ienumerable-1" target="_blank" rel="noopener noreferrer">IEnumerable</a>(*TSource*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_Jodo_Extensions_Collections_LookupExtensions">LookupExtensions Class</a><br /><a href="Overload_Jodo_Extensions_Collections_LookupExtensions_ToReadOnlyLookup">ToReadOnlyLookup Overload</a><br /><a href="N_Jodo_Extensions_Collections">Jodo.Extensions.Collections Namespace</a><br />
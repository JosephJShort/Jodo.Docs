# StreamExtensions.Read(*T*) Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

\[Missing <summary> documentation for "M:Jodo.Extensions.Primitives.StreamExtensions.Read``1(Jodo.Extensions.Primitives.IReadOnlyStream{System.Byte})"\]

**Namespace:**&nbsp;<a href="N_Jodo_Extensions_Primitives">Jodo.Extensions.Primitives</a><br />**Assembly:**&nbsp;Jodo.Extensions.Primitives (in Jodo.Extensions.Primitives.dll) Version: 1.1.0.0

## Syntax

**C#**<br />
``` C#
public static T Read<T>(
	this IReadOnlyStream<byte> stream
)
where T : struct, new(), IProvider<IBitConverter<T>>

```


#### Parameters
&nbsp;<dl><dt>stream</dt><dd>Type: <a href="T_Jodo_Extensions_Primitives_IReadOnlyStream_1">Jodo.Extensions.Primitives.IReadOnlyStream</a>(<a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">Byte</a>)<br />\[Missing <param name="stream"/> documentation for "M:Jodo.Extensions.Primitives.StreamExtensions.Read``1(Jodo.Extensions.Primitives.IReadOnlyStream{System.Byte})"\]</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:Jodo.Extensions.Primitives.StreamExtensions.Read``1(Jodo.Extensions.Primitives.IReadOnlyStream{System.Byte})"\]</dd></dl>

#### Return Value
Type: *T*<br />\[Missing <returns> documentation for "M:Jodo.Extensions.Primitives.StreamExtensions.Read``1(Jodo.Extensions.Primitives.IReadOnlyStream{System.Byte})"\]

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="T_Jodo_Extensions_Primitives_IReadOnlyStream_1">IReadOnlyStream</a>(<a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">Byte</a>). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_Jodo_Extensions_Primitives_StreamExtensions">StreamExtensions Class</a><br /><a href="N_Jodo_Extensions_Primitives">Jodo.Extensions.Primitives Namespace</a><br />
# Triangle(*N*) Structure
 _**\[This is preliminary documentation and is subject to change.\]**_

\[Missing <summary> documentation for "T:Jodo.Extensions.Geometry.Triangle`1"\]

**Namespace:**&nbsp;<a href="N_Jodo_Extensions_Geometry">Jodo.Extensions.Geometry</a><br />**Assembly:**&nbsp;Jodo.Extensions.Geometry (in Jodo.Extensions.Geometry.dll) Version: 1.1.0.0

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
public readonly struct Triangle<N> : IProvider<IBitConverter<Triangle<N>>>, 
	IProvider<IRandom<Triangle<N>>>, IProvider<IStringParser<Triangle<N>>>, 
	ITwoDimensional<Triangle<N>, N>, ISerializable
where N : struct, new(), INumeric<N>

```

<a href="https://github.com/JosephJShort/Jodo.Extensions/blob/main/src/Jodo.Extensions.Geometry/Triangle.cs" rel="noopener noreferrer" title="View the source code">View Source</a><br />

#### Type Parameters
&nbsp;<dl><dt>N</dt><dd>\[Missing <typeparam name="N"/> documentation for "T:Jodo.Extensions.Geometry.Triangle`1"\]</dd></dl>&nbsp;
The Triangle(N) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1__ctor">Triangle(N)</a></td><td>
Initializes a new instance of the Triangle(N) class</td></tr></table>&nbsp;
<a href="#triangle(*n*)-structure">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_Contains">Contains(Triangle(N))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_Contains_2">Contains(ValueTuple(N, N))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_Contains_1">Contains(Vector2(N))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_Contains_3">Contains(N, N)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_Convert__1">Convert(NResult)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_Equals_1">Equals(Object)</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.valuetype.equals#system-valuetype-equals(system-object)" target="_blank" rel="noopener noreferrer">ValueType.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_Equals">Equals(Triangle(N))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_GetArea">GetArea</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_GetBounds">GetBounds</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_GetCenter">GetCenter</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_GetHashCode">GetHashCode</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.valuetype.gethashcode#system-valuetype-gethashcode" target="_blank" rel="noopener noreferrer">ValueType.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_GetVertices">GetVertices</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_IntersectsWith">IntersectsWith</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_Parse">Parse(String)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_Parse_1">Parse(String, NumberStyles, IFormatProvider)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_Rotate">Rotate</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_Rotate90">Rotate90</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_RotateAround">RotateAround</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_ToString">ToString()</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.valuetype.tostring#system-valuetype-tostring" target="_blank" rel="noopener noreferrer">ValueType.ToString()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_ToString_1">ToString(String, IFormatProvider)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_Translate">Translate</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_TryParse">TryParse(String, Vector3(N))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_TryParse_1">TryParse(String, NumberStyles, IFormatProvider, Vector3(N))</a></td><td /></tr></table>&nbsp;
<a href="#triangle(*n*)-structure">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_op_Equality">Equality</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_op_Implicit">Implicit(Triangle(N) to ValueTuple(Vector2(N), Vector2(N), Vector2(N)))</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_op_Implicit_1">Implicit(ValueTuple(Vector2(N), Vector2(N), Vector2(N)) to Triangle(N))</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Geometry_Triangle_1_op_Inequality">Inequality</a></td><td /></tr></table>&nbsp;
<a href="#triangle(*n*)-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_Jodo_Extensions_Geometry_Triangle_1_A">A</a></td><td /></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_Jodo_Extensions_Geometry_Triangle_1_B">B</a></td><td /></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_Jodo_Extensions_Geometry_Triangle_1_C">C</a></td><td /></tr></table>&nbsp;
<a href="#triangle(*n*)-structure">Back to Top</a>

## See Also


#### Reference
<a href="N_Jodo_Extensions_Geometry">Jodo.Extensions.Geometry Namespace</a><br />
# Circle(*N*) Structure
 _**\[This is preliminary documentation and is subject to change.\]**_

\[Missing <summary> documentation for "T:Jodo.Extensions.Geometry.Circle`1"\]

**Namespace:**&nbsp;<a href="N_Jodo_Extensions_Geometry">Jodo.Extensions.Geometry</a><br />**Assembly:**&nbsp;Jodo.Extensions.Geometry (in Jodo.Extensions.Geometry.dll) Version: 1.1.0.0

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
public readonly struct Circle<N> : IProvider<IBitConverter<Circle<N>>>, 
	IProvider<IRandom<Circle<N>>>, IProvider<IStringParser<Circle<N>>>, 
	ITwoDimensional<Circle<N>, N>, ISerializable
where N : struct, new(), INumeric<N>

```

<a href="https://github.com/JosephJShort/Jodo.Extensions/blob/main/src/Jodo.Extensions.Geometry/Circle.cs" rel="noopener noreferrer" title="View the source code">View Source</a><br />

#### Type Parameters
&nbsp;<dl><dt>N</dt><dd>\[Missing <typeparam name="N"/> documentation for "T:Jodo.Extensions.Geometry.Circle`1"\]</dd></dl>&nbsp;
The Circle(N) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1__ctor">Circle(N)(Vector2(N), N)</a></td><td>
Initializes a new instance of the Circle(N) class</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1__ctor_1">Circle(N)(N, N, N)</a></td><td>
Initializes a new instance of the Circle(N) class</td></tr></table>&nbsp;
<a href="#circle(*n*)-structure">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_Contains">Contains(Circle(N))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_Contains_1">Contains(Vector2(N))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_Equals">Equals(Circle(N))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_Equals_1">Equals(Object)</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.valuetype.equals#system-valuetype-equals(system-object)" target="_blank" rel="noopener noreferrer">ValueType.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_GetArea">GetArea</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_GetBounds">GetBounds</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_GetCircumeference">GetCircumeference</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_GetDiameter">GetDiameter</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_GetHashCode">GetHashCode</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.valuetype.gethashcode#system-valuetype-gethashcode" target="_blank" rel="noopener noreferrer">ValueType.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_GetVertices">GetVertices</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_IntersectsWith">IntersectsWith</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_ToString">ToString()</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.valuetype.tostring#system-valuetype-tostring" target="_blank" rel="noopener noreferrer">ValueType.ToString()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_ToString_1">ToString(String, IFormatProvider)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_Translate">Translate(Vector2(N))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_Translate_1">Translate(N, N)</a></td><td /></tr></table>&nbsp;
<a href="#circle(*n*)-structure">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_op_Equality">Equality</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Geometry_Circle_1_op_Inequality">Inequality</a></td><td /></tr></table>&nbsp;
<a href="#circle(*n*)-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_Jodo_Extensions_Geometry_Circle_1_Center">Center</a></td><td /></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_Jodo_Extensions_Geometry_Circle_1_Radius">Radius</a></td><td /></tr></table>&nbsp;
<a href="#circle(*n*)-structure">Back to Top</a>

## See Also


#### Reference
<a href="N_Jodo_Extensions_Geometry">Jodo.Extensions.Geometry Namespace</a><br />
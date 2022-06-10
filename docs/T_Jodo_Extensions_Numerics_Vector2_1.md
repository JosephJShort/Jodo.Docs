# Vector2(*N*) Structure
 _**\[This is preliminary documentation and is subject to change.\]**_

\[Missing <summary> documentation for "T:Jodo.Extensions.Numerics.Vector2`1"\]

**Namespace:**&nbsp;<a href="N_Jodo_Extensions_Numerics">Jodo.Extensions.Numerics</a><br />**Assembly:**&nbsp;Jodo.Extensions.Numerics (in Jodo.Extensions.Numerics.dll) Version: 1.1.0.0

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
public readonly struct Vector2<N> : IProvider<IBitConverter<Vector2<N>>>, 
	IProvider<IRandom<Vector2<N>>>, IProvider<IStringParser<Vector2<N>>>, 
	ISerializable
where N : struct, new(), INumeric<N>

```

<a href="https://github.com/JosephJShort/Jodo.Extensions/blob/main/src/Jodo.Extensions.Numerics/Vector2.cs" rel="noopener noreferrer" title="View the source code">View Source</a><br />

#### Type Parameters
&nbsp;<dl><dt>N</dt><dd>\[Missing <typeparam name="N"/> documentation for "T:Jodo.Extensions.Numerics.Vector2`1"\]</dd></dl>&nbsp;
The Vector2(N) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1__ctor">Vector2(N)</a></td><td>
Initializes a new instance of the Vector2(N) class</td></tr></table>&nbsp;
<a href="#vector2(*n*)-structure">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_Convert__1">Convert(NResult)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_Equals_1">Equals(Object)</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.valuetype.equals#system-valuetype-equals(system-object)" target="_blank" rel="noopener noreferrer">ValueType.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_Equals">Equals(Vector2(N))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_GetHashCode">GetHashCode</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.valuetype.gethashcode#system-valuetype-gethashcode" target="_blank" rel="noopener noreferrer">ValueType.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_Parse">Parse(String)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_Parse_1">Parse(String, NumberStyles, IFormatProvider)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_ToString">ToString()</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.valuetype.tostring#system-valuetype-tostring" target="_blank" rel="noopener noreferrer">ValueType.ToString()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_ToString_1">ToString(String, IFormatProvider)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_TryParse">TryParse(String, Vector2(N))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_TryParse_1">TryParse(String, NumberStyles, IFormatProvider, Vector2(N))</a></td><td /></tr></table>&nbsp;
<a href="#vector2(*n*)-structure">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_op_Addition">Addition</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_op_Division">Division</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_op_Equality">Equality</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_op_Implicit_2">Implicit(Tuple(N, N) to Vector2(N))</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_op_Implicit_3">Implicit(ValueTuple(N, N) to Vector2(N))</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_op_Implicit_1">Implicit(Vector2(N) to Tuple(N, N))</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_op_Implicit">Implicit(Vector2(N) to ValueTuple(N, N))</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_op_Inequality">Inequality</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_op_Multiply_1">Multiply(N, Vector2(N))</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_op_Multiply">Multiply(Vector2(N), N)</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_op_Subtraction">Subtraction</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_op_UnaryNegation">UnaryNegation</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector2_1_op_UnaryPlus">UnaryPlus</a></td><td /></tr></table>&nbsp;
<a href="#vector2(*n*)-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_Jodo_Extensions_Numerics_Vector2_1_X">X</a></td><td /></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_Jodo_Extensions_Numerics_Vector2_1_Y">Y</a></td><td /></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_Jodo_Extensions_Numerics_Vector2_1_Zero">Zero</a></td><td /></tr></table>&nbsp;
<a href="#vector2(*n*)-structure">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Jodo_Extensions_Geometry_VectorExtensions_DistanceFrom__1">DistanceFrom(N)</a></td><td> (Defined by <a href="T_Jodo_Extensions_Geometry_VectorExtensions">VectorExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Jodo_Extensions_Geometry_VectorExtensions_GetLength__1">GetLength(N)</a></td><td> (Defined by <a href="T_Jodo_Extensions_Geometry_VectorExtensions">VectorExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Jodo_Extensions_Geometry_VectorExtensions_GetLengthSquared__1">GetLengthSquared(N)</a></td><td> (Defined by <a href="T_Jodo_Extensions_Geometry_VectorExtensions">VectorExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Jodo_Extensions_Geometry_VectorExtensions_RotateAround__1">RotateAround(N)</a></td><td> (Defined by <a href="T_Jodo_Extensions_Geometry_VectorExtensions">VectorExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Jodo_Extensions_Geometry_VectorExtensions_Translate__1">Translate(N)</a></td><td> (Defined by <a href="T_Jodo_Extensions_Geometry_VectorExtensions">VectorExtensions</a>.)</td></tr></table>&nbsp;
<a href="#vector2(*n*)-structure">Back to Top</a>

## See Also


#### Reference
<a href="N_Jodo_Extensions_Numerics">Jodo.Extensions.Numerics Namespace</a><br />
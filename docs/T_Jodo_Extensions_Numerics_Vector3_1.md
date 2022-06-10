# Vector3(*N*) Structure
 _**\[This is preliminary documentation and is subject to change.\]**_

\[Missing <summary> documentation for "T:Jodo.Extensions.Numerics.Vector3`1"\]

**Namespace:**&nbsp;<a href="N_Jodo_Extensions_Numerics">Jodo.Extensions.Numerics</a><br />**Assembly:**&nbsp;Jodo.Extensions.Numerics (in Jodo.Extensions.Numerics.dll) Version: 1.1.0.0

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
public readonly struct Vector3<N> : IProvider<IBitConverter<Vector3<N>>>, 
	IProvider<IRandom<Vector3<N>>>, IProvider<IStringParser<Vector3<N>>>, 
	ISerializable
where N : struct, new(), INumeric<N>

```

<a href="https://github.com/JosephJShort/Jodo.Extensions/blob/main/src/Jodo.Extensions.Numerics/Vector3.cs" rel="noopener noreferrer" title="View the source code">View Source</a><br />

#### Type Parameters
&nbsp;<dl><dt>N</dt><dd>\[Missing <typeparam name="N"/> documentation for "T:Jodo.Extensions.Numerics.Vector3`1"\]</dd></dl>&nbsp;
The Vector3(N) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1__ctor">Vector3(N)</a></td><td>
Initializes a new instance of the Vector3(N) class</td></tr></table>&nbsp;
<a href="#vector3(*n*)-structure">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_Equals_1">Equals(Object)</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.valuetype.equals#system-valuetype-equals(system-object)" target="_blank" rel="noopener noreferrer">ValueType.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_Equals">Equals(Vector3(N))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_GetHashCode">GetHashCode</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.valuetype.gethashcode#system-valuetype-gethashcode" target="_blank" rel="noopener noreferrer">ValueType.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_Parse">Parse(String)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_Parse_1">Parse(String, NumberStyles, IFormatProvider)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_ToString">ToString()</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.valuetype.tostring#system-valuetype-tostring" target="_blank" rel="noopener noreferrer">ValueType.ToString()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_ToString_1">ToString(String, IFormatProvider)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_TryParse">TryParse(String, Vector3(N))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_TryParse_1">TryParse(String, NumberStyles, IFormatProvider, Vector3(N))</a></td><td /></tr></table>&nbsp;
<a href="#vector3(*n*)-structure">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_op_Addition">Addition</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_op_Division">Division</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_op_Equality">Equality</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_op_Implicit_2">Implicit(Tuple(N, N, N) to Vector3(N))</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_op_Implicit_3">Implicit(ValueTuple(N, N, N) to Vector3(N))</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_op_Implicit_1">Implicit(Vector3(N) to Tuple(N, N, N))</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_op_Implicit">Implicit(Vector3(N) to ValueTuple(N, N, N))</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_op_Inequality">Inequality</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_op_Multiply_1">Multiply(N, Vector3(N))</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_op_Multiply">Multiply(Vector3(N), N)</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_op_Subtraction">Subtraction</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_op_UnaryNegation">UnaryNegation</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Jodo_Extensions_Numerics_Vector3_1_op_UnaryPlus">UnaryPlus</a></td><td /></tr></table>&nbsp;
<a href="#vector3(*n*)-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_Jodo_Extensions_Numerics_Vector3_1_X">X</a></td><td /></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_Jodo_Extensions_Numerics_Vector3_1_Y">Y</a></td><td /></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_Jodo_Extensions_Numerics_Vector3_1_Z">Z</a></td><td /></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_Jodo_Extensions_Numerics_Vector3_1_Zero">Zero</a></td><td /></tr></table>&nbsp;
<a href="#vector3(*n*)-structure">Back to Top</a>

## See Also


#### Reference
<a href="N_Jodo_Extensions_Numerics">Jodo.Extensions.Numerics Namespace</a><br />
# Class PriorityAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Defines this command overload's priority. This determines the order in which overloads will be attempted to be called. Commands will be attempted in order of priority, in descending order.

```csharp
[AttributeUsage(AttributeTargets.Method, AllowMultiple = false, Inherited = false)]
public sealed class PriorityAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[PriorityAttribute](DSharpPlus.CommandsNext.Attributes.PriorityAttribute.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_Attributes_PriorityAttribute__ctor_System_Int32_"></a>PriorityAttribute\(int\)

Defines this command overload's priority. This determines the order in which overloads will be attempted to be called. Commands will be attempted in order of priority, in descending order.

```csharp
public PriorityAttribute(int priority)
```

#### Parameters

`priority` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Priority of this command overload.

## Properties

### <a id="DSharpPlus_CommandsNext_Attributes_PriorityAttribute_Priority"></a>Priority

Gets the priority of this command overload.

```csharp
public int Priority { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)


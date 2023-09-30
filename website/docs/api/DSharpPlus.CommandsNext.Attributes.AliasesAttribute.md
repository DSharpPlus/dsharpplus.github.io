# Class AliasesAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Adds aliases to this command or group.

```csharp
[AttributeUsage(AttributeTargets.Class|AttributeTargets.Method, AllowMultiple = false)]
public sealed class AliasesAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[AliasesAttribute](DSharpPlus.CommandsNext.Attributes.AliasesAttribute.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_Attributes_AliasesAttribute__ctor_System_String___"></a>AliasesAttribute\(params string\[\]\)

Adds aliases to this command or group.

```csharp
public AliasesAttribute(params string[] aliases)
```

#### Parameters

`aliases` [string](https://learn.microsoft.com/dotnet/api/system.string)\[\]

Aliases to add to this command or group.

## Properties

### <a id="DSharpPlus_CommandsNext_Attributes_AliasesAttribute_Aliases"></a>Aliases

Gets this group's aliases.

```csharp
public IReadOnlyList<string> Aliases { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>


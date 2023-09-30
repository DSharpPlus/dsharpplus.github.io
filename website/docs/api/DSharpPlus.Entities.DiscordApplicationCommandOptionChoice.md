# Class DiscordApplicationCommandOptionChoice

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a command parameter choice for a <xref href="DSharpPlus.Entities.DiscordApplicationCommandOption" data-throw-if-not-resolved="false"></xref>.

```csharp
public sealed class DiscordApplicationCommandOptionChoice
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordApplicationCommandOptionChoice](DSharpPlus.Entities.DiscordApplicationCommandOptionChoice.md)

## Constructors

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOptionChoice__ctor_System_String_System_Object_"></a>DiscordApplicationCommandOptionChoice\(string, object\)

Creates a new instance of a <xref href="DSharpPlus.Entities.DiscordApplicationCommandOptionChoice" data-throw-if-not-resolved="false"></xref>.

```csharp
public DiscordApplicationCommandOptionChoice(string name, object value)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the parameter choice.

`value` [object](https://learn.microsoft.com/dotnet/api/system.object)

The value of the parameter choice.

## Properties

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOptionChoice_Name"></a>Name

Gets the name of this choice parameter.

```csharp
[JsonProperty("name")]
public string Name { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOptionChoice_Value"></a>Value

Gets the value of this choice parameter. This will either be a type of <xref href="System.Int32" data-throw-if-not-resolved="false"></xref> / <xref href="System.Int64" data-throw-if-not-resolved="false"></xref>, <xref href="System.Double" data-throw-if-not-resolved="false"></xref> or <xref href="System.String" data-throw-if-not-resolved="false"></xref>.

```csharp
[JsonProperty("value")]
public object Value { get; set; }
```

#### Property Value

[object](https://learn.microsoft.com/dotnet/api/system.object)


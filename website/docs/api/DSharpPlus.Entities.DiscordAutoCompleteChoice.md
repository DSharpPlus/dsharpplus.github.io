# Class DiscordAutoCompleteChoice

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents an option for a user to select for auto-completion.

```csharp
public sealed class DiscordAutoCompleteChoice
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordAutoCompleteChoice](DSharpPlus.Entities.DiscordAutoCompleteChoice.md)

## Constructors

### <a id="DSharpPlus_Entities_DiscordAutoCompleteChoice__ctor_System_String_System_Object_"></a>DiscordAutoCompleteChoice\(string, object\)

Creates a new instance of <xref href="DSharpPlus.Entities.DiscordAutoCompleteChoice" data-throw-if-not-resolved="false"></xref>.

```csharp
public DiscordAutoCompleteChoice(string name, object value)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of this option, which will be presented to the user.

`value` [object](https://learn.microsoft.com/dotnet/api/system.object)

The value of this option.

## Properties

### <a id="DSharpPlus_Entities_DiscordAutoCompleteChoice_Name"></a>Name

Gets the name of this option which will be presented to the user.

```csharp
[JsonProperty("name")]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordAutoCompleteChoice_Value"></a>Value

Gets the value of this option. This may be a string or an integer.

```csharp
[JsonProperty("value")]
public object Value { get; }
```

#### Property Value

[object](https://learn.microsoft.com/dotnet/api/system.object)


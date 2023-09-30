# Class AutocompleteAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Handles autocomplete choices for a slash command parameter.

```csharp
[AttributeUsage(AttributeTargets.Parameter, AllowMultiple = false)]
public class AutocompleteAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[AutocompleteAttribute](DSharpPlus.SlashCommands.AutocompleteAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_AutocompleteAttribute__ctor_System_Type_"></a>AutocompleteAttribute\(Type\)

Handles autocomplete choices for a slash command parameter.

```csharp
public AutocompleteAttribute(Type provider)
```

#### Parameters

`provider` [Type](https://learn.microsoft.com/dotnet/api/system.type)

The type of the autocomplete provider. This should inherit from <xref href="DSharpPlus.SlashCommands.IAutocompleteProvider" data-throw-if-not-resolved="false"></xref>.

## Properties

### <a id="DSharpPlus_SlashCommands_AutocompleteAttribute_Provider"></a>Provider

The provider for this autocomplete parameter.

```csharp
public Type Provider { get; }
```

#### Property Value

[Type](https://learn.microsoft.com/dotnet/api/system.type)


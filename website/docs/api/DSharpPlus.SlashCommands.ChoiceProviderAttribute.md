# Class ChoiceProviderAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Sets a IChoiceProvider for a command options. ChoiceProviders can be used to provide
DiscordApplicationCommandOptionChoice from external sources such as a database.

```csharp
[AttributeUsage(AttributeTargets.Parameter, AllowMultiple = true)]
public sealed class ChoiceProviderAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[ChoiceProviderAttribute](DSharpPlus.SlashCommands.ChoiceProviderAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_ChoiceProviderAttribute__ctor_System_Type_"></a>ChoiceProviderAttribute\(Type\)

Adds a choice provider to this command.

```csharp
public ChoiceProviderAttribute(Type providerType)
```

#### Parameters

`providerType` [Type](https://learn.microsoft.com/dotnet/api/system.type)

The type of the provider.

## Properties

### <a id="DSharpPlus_SlashCommands_ChoiceProviderAttribute_ProviderType"></a>ProviderType

The type of the provider.

```csharp
public Type ProviderType { get; }
```

#### Property Value

[Type](https://learn.microsoft.com/dotnet/api/system.type)


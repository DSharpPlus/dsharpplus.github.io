# Class NameLocalizationAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Specifies a locale for a slash command name. The longest name is the name that counts toward character limits.

```csharp
[AttributeUsage(AttributeTargets.Class|AttributeTargets.Method|AttributeTargets.Parameter, AllowMultiple = true)]
public sealed class NameLocalizationAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[NameLocalizationAttribute](DSharpPlus.SlashCommands.NameLocalizationAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_NameLocalizationAttribute__ctor_DSharpPlus_SlashCommands_Localization_System_String_"></a>NameLocalizationAttribute\(Localization, string\)

```csharp
public NameLocalizationAttribute(Localization locale, string name)
```

#### Parameters

`locale` [Localization](DSharpPlus.SlashCommands.Localization.md)

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

## Properties

### <a id="DSharpPlus_SlashCommands_NameLocalizationAttribute_Locale"></a>Locale

```csharp
public string Locale { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_SlashCommands_NameLocalizationAttribute_Name"></a>Name

```csharp
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)


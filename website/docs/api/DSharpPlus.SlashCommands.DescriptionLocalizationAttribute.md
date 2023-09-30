# Class DescriptionLocalizationAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Specifies a locale for a slash command description. The longest description is the one that counts toward character limits.

```csharp
[AttributeUsage(AttributeTargets.Class|AttributeTargets.Method|AttributeTargets.Parameter, AllowMultiple = true)]
public sealed class DescriptionLocalizationAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[DescriptionLocalizationAttribute](DSharpPlus.SlashCommands.DescriptionLocalizationAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_DescriptionLocalizationAttribute__ctor_DSharpPlus_SlashCommands_Localization_System_String_"></a>DescriptionLocalizationAttribute\(Localization, string\)

```csharp
public DescriptionLocalizationAttribute(Localization locale, string description)
```

#### Parameters

`locale` [Localization](DSharpPlus.SlashCommands.Localization.md)

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

## Properties

### <a id="DSharpPlus_SlashCommands_DescriptionLocalizationAttribute_Description"></a>Description

```csharp
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_SlashCommands_DescriptionLocalizationAttribute_Locale"></a>Locale

```csharp
public string Locale { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)


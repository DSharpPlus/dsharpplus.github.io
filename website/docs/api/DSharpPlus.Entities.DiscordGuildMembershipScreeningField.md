# Class DiscordGuildMembershipScreeningField

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a field in a guild's membership screening form

```csharp
public class DiscordGuildMembershipScreeningField
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordGuildMembershipScreeningField](DSharpPlus.Entities.DiscordGuildMembershipScreeningField.md)

## Constructors

### <a id="DSharpPlus_Entities_DiscordGuildMembershipScreeningField__ctor_DSharpPlus_MembershipScreeningFieldType_System_String_System_Collections_Generic_IEnumerable_System_String__System_Boolean_"></a>DiscordGuildMembershipScreeningField\(MembershipScreeningFieldType, string, IEnumerable<string\>, bool\)

```csharp
public DiscordGuildMembershipScreeningField(MembershipScreeningFieldType type, string label, IEnumerable<string> values, bool required = true)
```

#### Parameters

`type` [MembershipScreeningFieldType](DSharpPlus.MembershipScreeningFieldType.md)

`label` [string](https://learn.microsoft.com/dotnet/api/system.string)

`values` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

`required` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

## Properties

### <a id="DSharpPlus_Entities_DiscordGuildMembershipScreeningField_IsRequired"></a>IsRequired

Gets whether the user has to fill out this field

```csharp
[JsonProperty("required", NullValueHandling = NullValueHandling.Ignore)]
public bool IsRequired { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordGuildMembershipScreeningField_Label"></a>Label

Gets the title of the field.

```csharp
[JsonProperty("label", NullValueHandling = NullValueHandling.Ignore)]
public string Label { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuildMembershipScreeningField_Type"></a>Type

Gets the type of the field.

```csharp
[JsonProperty("field_type", NullValueHandling = NullValueHandling.Ignore)]
public MembershipScreeningFieldType Type { get; }
```

#### Property Value

[MembershipScreeningFieldType](DSharpPlus.MembershipScreeningFieldType.md)

### <a id="DSharpPlus_Entities_DiscordGuildMembershipScreeningField_Values"></a>Values

Gets the list of rules

```csharp
[JsonProperty("values", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<string> Values { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>


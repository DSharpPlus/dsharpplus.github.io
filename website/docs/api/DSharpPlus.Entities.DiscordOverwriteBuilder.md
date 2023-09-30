# Class DiscordOverwriteBuilder

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord permission overwrite builder.

```csharp
public sealed class DiscordOverwriteBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordOverwriteBuilder](DSharpPlus.Entities.DiscordOverwriteBuilder.md)

## Constructors

### <a id="DSharpPlus_Entities_DiscordOverwriteBuilder__ctor_DSharpPlus_Entities_DiscordMember_"></a>DiscordOverwriteBuilder\(DiscordMember\)

Creates a new Discord permission overwrite builder for a member. This class can be used to construct permission overwrites for guild channels, used when creating channels.

```csharp
public DiscordOverwriteBuilder(DiscordMember member)
```

#### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

### <a id="DSharpPlus_Entities_DiscordOverwriteBuilder__ctor_DSharpPlus_Entities_DiscordRole_"></a>DiscordOverwriteBuilder\(DiscordRole\)

Creates a new Discord permission overwrite builder for a role. This class can be used to construct permission overwrites for guild channels, used when creating channels.

```csharp
public DiscordOverwriteBuilder(DiscordRole role)
```

#### Parameters

`role` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordOverwriteBuilder_Allowed"></a>Allowed

Gets or sets the allowed permissions for this overwrite.

```csharp
public Permissions Allowed { get; set; }
```

#### Property Value

[Permissions](DSharpPlus.Permissions.md)

### <a id="DSharpPlus_Entities_DiscordOverwriteBuilder_Denied"></a>Denied

Gets or sets the denied permissions for this overwrite.

```csharp
public Permissions Denied { get; set; }
```

#### Property Value

[Permissions](DSharpPlus.Permissions.md)

### <a id="DSharpPlus_Entities_DiscordOverwriteBuilder_Target"></a>Target

Gets the target for this overwrite.

```csharp
public SnowflakeObject Target { get; }
```

#### Property Value

[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md)

### <a id="DSharpPlus_Entities_DiscordOverwriteBuilder_Type"></a>Type

Gets the type of this overwrite's target.

```csharp
public OverwriteType Type { get; }
```

#### Property Value

[OverwriteType](DSharpPlus.OverwriteType.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordOverwriteBuilder_Allow_DSharpPlus_Permissions_"></a>Allow\(Permissions\)

Allows a permission for this overwrite.

```csharp
public DiscordOverwriteBuilder Allow(Permissions permission)
```

#### Parameters

`permission` [Permissions](DSharpPlus.Permissions.md)

Permission or permission set to allow for this overwrite.

#### Returns

[DiscordOverwriteBuilder](DSharpPlus.Entities.DiscordOverwriteBuilder.md)

This builder.

### <a id="DSharpPlus_Entities_DiscordOverwriteBuilder_Deny_DSharpPlus_Permissions_"></a>Deny\(Permissions\)

Denies a permission for this overwrite.

```csharp
public DiscordOverwriteBuilder Deny(Permissions permission)
```

#### Parameters

`permission` [Permissions](DSharpPlus.Permissions.md)

Permission or permission set to deny for this overwrite.

#### Returns

[DiscordOverwriteBuilder](DSharpPlus.Entities.DiscordOverwriteBuilder.md)

This builder.

### <a id="DSharpPlus_Entities_DiscordOverwriteBuilder_For_DSharpPlus_Entities_DiscordMember_"></a>For\(DiscordMember\)

Sets the member to which this overwrite applies.

```csharp
public DiscordOverwriteBuilder For(DiscordMember member)
```

#### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

Member to which apply this overwrite's permissions.

#### Returns

[DiscordOverwriteBuilder](DSharpPlus.Entities.DiscordOverwriteBuilder.md)

This builder.

### <a id="DSharpPlus_Entities_DiscordOverwriteBuilder_For_DSharpPlus_Entities_DiscordRole_"></a>For\(DiscordRole\)

Sets the role to which this overwrite applies.

```csharp
public DiscordOverwriteBuilder For(DiscordRole role)
```

#### Parameters

`role` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

Role to which apply this overwrite's permissions.

#### Returns

[DiscordOverwriteBuilder](DSharpPlus.Entities.DiscordOverwriteBuilder.md)

This builder.

### <a id="DSharpPlus_Entities_DiscordOverwriteBuilder_FromAsync_DSharpPlus_Entities_DiscordOverwrite_"></a>FromAsync\(DiscordOverwrite\)

Populates this builder with data from another overwrite object.

```csharp
public Task<DiscordOverwriteBuilder> FromAsync(DiscordOverwrite other)
```

#### Parameters

`other` [DiscordOverwrite](DSharpPlus.Entities.DiscordOverwrite.md)

Overwrite from which data will be used.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordOverwriteBuilder](DSharpPlus.Entities.DiscordOverwriteBuilder.md)\>

This builder.


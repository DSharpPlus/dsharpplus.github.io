# Struct RoleMention

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Allows @role pings to mention in the message.

```csharp
public readonly struct RoleMention : IMention
```

###### Implements

[IMention](DSharpPlus.Entities.IMention.md)

## Constructors

### <a id="DSharpPlus_Entities_RoleMention__ctor_System_UInt64_"></a>RoleMention\(ulong\)

Allows the specific id to be mentioned

```csharp
public RoleMention(ulong id)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_RoleMention__ctor_DSharpPlus_Entities_DiscordRole_"></a>RoleMention\(DiscordRole\)

Allows the specific role to be mentioned

```csharp
public RoleMention(DiscordRole role)
```

#### Parameters

`role` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

## Fields

### <a id="DSharpPlus_Entities_RoleMention_All"></a>All

Allow the mentioning of all roles.  Alias to <xref href="DSharpPlus.Entities.RoleMention.%23ctor" data-throw-if-not-resolved="false"></xref> constructor.

```csharp
public static readonly RoleMention All
```

#### Field Value

[RoleMention](DSharpPlus.Entities.RoleMention.md)

## Properties

### <a id="DSharpPlus_Entities_RoleMention_Id"></a>Id

Optional Id of the role that is allowed to be mentioned. If null, then all role mentions will be allowed.

```csharp
public ulong? Id { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

## Operators

### <a id="DSharpPlus_Entities_RoleMention_op_Implicit_DSharpPlus_Entities_DiscordRole__DSharpPlus_Entities_RoleMention"></a>implicit operator RoleMention\(DiscordRole\)

```csharp
public static implicit operator RoleMention(DiscordRole role)
```

#### Parameters

`role` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

#### Returns

[RoleMention](DSharpPlus.Entities.RoleMention.md)


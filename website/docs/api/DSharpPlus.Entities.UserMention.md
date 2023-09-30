# Struct UserMention

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Allows @user pings to mention in the message.

```csharp
public readonly struct UserMention : IMention
```

###### Implements

[IMention](DSharpPlus.Entities.IMention.md)

## Constructors

### <a id="DSharpPlus_Entities_UserMention__ctor_System_UInt64_"></a>UserMention\(ulong\)

Allows the specific user to be mentioned

```csharp
public UserMention(ulong id)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_UserMention__ctor_DSharpPlus_Entities_DiscordUser_"></a>UserMention\(DiscordUser\)

Allows the specific user to be mentioned

```csharp
public UserMention(DiscordUser user)
```

#### Parameters

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

## Fields

### <a id="DSharpPlus_Entities_UserMention_All"></a>All

Allow mentioning of all users. Alias to <xref href="DSharpPlus.Entities.UserMention.%23ctor" data-throw-if-not-resolved="false"></xref> constructor.

```csharp
public static readonly UserMention All
```

#### Field Value

[UserMention](DSharpPlus.Entities.UserMention.md)

## Properties

### <a id="DSharpPlus_Entities_UserMention_Id"></a>Id

Optional Id of the user that is allowed to be mentioned. If null, then all user mentions will be allowed.

```csharp
public ulong? Id { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

## Operators

### <a id="DSharpPlus_Entities_UserMention_op_Implicit_DSharpPlus_Entities_DiscordUser__DSharpPlus_Entities_UserMention"></a>implicit operator UserMention\(DiscordUser\)

```csharp
public static implicit operator UserMention(DiscordUser user)
```

#### Parameters

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

#### Returns

[UserMention](DSharpPlus.Entities.UserMention.md)


# Class RoleEditModel

Namespace: [DSharpPlus.Net.Models](DSharpPlus.Net.Models.md)  
Assembly: DSharpPlus.dll

```csharp
public class RoleEditModel : BaseEditModel
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseEditModel](DSharpPlus.Net.Models.BaseEditModel.md) ← 
[RoleEditModel](DSharpPlus.Net.Models.RoleEditModel.md)

###### Inherited Members

[BaseEditModel.AuditLogReason](DSharpPlus.Net.Models.BaseEditModel.md\#DSharpPlus\_Net\_Models\_BaseEditModel\_AuditLogReason)

## Properties

### <a id="DSharpPlus_Net_Models_RoleEditModel_Color"></a>Color

New role color

```csharp
public DiscordColor? Color { set; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)?

### <a id="DSharpPlus_Net_Models_RoleEditModel_Emoji"></a>Emoji

The emoji to set for role role icon; must be unicode.

```csharp
public DiscordEmoji Emoji { set; }
```

#### Property Value

[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

### <a id="DSharpPlus_Net_Models_RoleEditModel_Hoist"></a>Hoist

Whether new role should be hoisted

```csharp
public bool? Hoist { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Net_Models_RoleEditModel_Icon"></a>Icon

The stream to use for uploading a new role icon.

```csharp
public Stream Icon { set; }
```

#### Property Value

[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

### <a id="DSharpPlus_Net_Models_RoleEditModel_Mentionable"></a>Mentionable

Whether new role should be mentionable

```csharp
public bool? Mentionable { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Net_Models_RoleEditModel_Name"></a>Name

New role name

```csharp
public string Name { set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Net_Models_RoleEditModel_Permissions"></a>Permissions

New role permissions

```csharp
public Permissions? Permissions { set; }
```

#### Property Value

[Permissions](DSharpPlus.Permissions.md)?


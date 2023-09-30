# Class ApplicationCommandEditModel

Namespace: [DSharpPlus.Net.Models](DSharpPlus.Net.Models.md)  
Assembly: DSharpPlus.dll

```csharp
public class ApplicationCommandEditModel
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ApplicationCommandEditModel](DSharpPlus.Net.Models.ApplicationCommandEditModel.md)

## Properties

### <a id="DSharpPlus_Net_Models_ApplicationCommandEditModel_AllowDMUsage"></a>AllowDMUsage

Sets whether the command can be invoked in DMs.

```csharp
public Optional<bool> AllowDMUsage { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

### <a id="DSharpPlus_Net_Models_ApplicationCommandEditModel_DefaultMemberPermissions"></a>DefaultMemberPermissions

Sets the requisite permissions for the command.

```csharp
public Optional<Permissions?> DefaultMemberPermissions { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[Permissions](DSharpPlus.Permissions.md)?\>

### <a id="DSharpPlus_Net_Models_ApplicationCommandEditModel_DefaultPermission"></a>DefaultPermission

Sets whether the command is enabled by default when the application is added to a guild.

```csharp
public Optional<bool?> DefaultPermission { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?\>

### <a id="DSharpPlus_Net_Models_ApplicationCommandEditModel_Description"></a>Description

Sets the command's new description

```csharp
public Optional<string> Description { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Net_Models_ApplicationCommandEditModel_NSFW"></a>NSFW

Sets whether this command is age restricted.

```csharp
public Optional<bool?> NSFW { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?\>

### <a id="DSharpPlus_Net_Models_ApplicationCommandEditModel_Name"></a>Name

Sets the command's new name.

```csharp
public Optional<string> Name { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Net_Models_ApplicationCommandEditModel_Options"></a>Options

Sets the command's new options.

```csharp
public Optional<IReadOnlyCollection<DiscordApplicationCommandOption>> Options { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[DiscordApplicationCommandOption](DSharpPlus.Entities.DiscordApplicationCommandOption.md)\>\>


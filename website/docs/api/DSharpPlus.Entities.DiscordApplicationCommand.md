# Class DiscordApplicationCommand

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a command that is registered to an application.

```csharp
public sealed class DiscordApplicationCommand : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Constructors

### <a id="DSharpPlus_Entities_DiscordApplicationCommand__ctor_System_String_System_String_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommandOption__System_Nullable_System_Boolean__DSharpPlus_ApplicationCommandType_System_Collections_Generic_IReadOnlyDictionary_System_String_System_String__System_Collections_Generic_IReadOnlyDictionary_System_String_System_String__System_Nullable_System_Boolean__System_Nullable_DSharpPlus_Permissions__System_Nullable_System_Boolean__"></a>DiscordApplicationCommand\(string, string, IEnumerable<DiscordApplicationCommandOption\>, bool?, ApplicationCommandType, IReadOnlyDictionary<string, string\>, IReadOnlyDictionary<string, string\>, bool?, Permissions?, bool?\)

Creates a new instance of a <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref>.

```csharp
public DiscordApplicationCommand(string name, string description, IEnumerable<DiscordApplicationCommandOption> options = null, bool? defaultPermission = null, ApplicationCommandType type = ApplicationCommandType.SlashCommand, IReadOnlyDictionary<string, string> name_localizations = null, IReadOnlyDictionary<string, string> description_localizations = null, bool? allowDMUsage = null, Permissions? defaultMemberPermissions = null, bool? nsfw = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the command.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

The description of the command.

`options` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommandOption](DSharpPlus.Entities.DiscordApplicationCommandOption.md)\>

Optional parameters for this command.

`defaultPermission` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether the command is enabled by default when the application is added to a guild.

`type` [ApplicationCommandType](DSharpPlus.ApplicationCommandType.md)

The type of the application command

`name\_localizations` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

Localization dictionary for <code class="paramref">name</code> field. Values follow the same restrictions as <code class="paramref">name</code>.

`description\_localizations` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

Localization dictionary for <code class="paramref">description</code> field. Values follow the same restrictions as <code class="paramref">description</code>.

`allowDMUsage` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this command can be invoked in DMs.

`defaultMemberPermissions` [Permissions](DSharpPlus.Permissions.md)?

What permissions this command requires to be invoked.

`nsfw` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether the command is age restricted.

## Properties

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_AllowDMUsage"></a>AllowDMUsage

Whether this command can be invoked in DMs.

```csharp
[JsonProperty("dm_permission")]
public bool? AllowDMUsage { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_ApplicationId"></a>ApplicationId

Gets the unique ID of this command's application.

```csharp
[JsonProperty("application_id")]
public ulong ApplicationId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_DefaultMemberPermissions"></a>DefaultMemberPermissions

What permissions this command requires to be invoked.

```csharp
[JsonProperty("default_member_permissions")]
public Permissions? DefaultMemberPermissions { get; }
```

#### Property Value

[Permissions](DSharpPlus.Permissions.md)?

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_DefaultPermission"></a>DefaultPermission

Gets whether the command is enabled by default when the application is added to a guild.

```csharp
[JsonProperty("default_permission")]
public bool? DefaultPermission { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_Description"></a>Description

Gets the description of this command.

```csharp
[JsonProperty("description")]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_DescriptionLocalizations"></a>DescriptionLocalizations

```csharp
[JsonProperty("description_localizations")]
public IReadOnlyDictionary<string, string> DescriptionLocalizations { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_Mention"></a>Mention

Gets the command's mention string.

```csharp
[JsonIgnore]
public string Mention { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_NSFW"></a>NSFW

Whether this command is age-restricted.

```csharp
[JsonProperty("nsfw")]
public bool? NSFW { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_Name"></a>Name

Gets the name of this command.

```csharp
[JsonProperty("name")]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_NameLocalizations"></a>NameLocalizations

```csharp
[JsonProperty("name_localizations")]
public IReadOnlyDictionary<string, string> NameLocalizations { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_Options"></a>Options

Gets the potential parameters for this command.

```csharp
[JsonProperty("options", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyCollection<DiscordApplicationCommandOption> Options { get; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[DiscordApplicationCommandOption](DSharpPlus.Entities.DiscordApplicationCommandOption.md)\>

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_Type"></a>Type

Gets the type of this application command.

```csharp
[JsonProperty("type")]
public ApplicationCommandType Type { get; }
```

#### Property Value

[ApplicationCommandType](DSharpPlus.ApplicationCommandType.md)

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_Version"></a>Version

Gets the auto-incrementing version number for this command.

```csharp
[JsonProperty("version")]
public ulong Version { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

## Methods

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_Equals_DSharpPlus_Entities_DiscordApplicationCommand_"></a>Equals\(DiscordApplicationCommand\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref> object is equal to another object.

```csharp
public bool Equals(DiscordApplicationCommand other)
```

#### Parameters

`other` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The command to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the command is equal to this <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_Equals_System_Object_"></a>Equals\(object\)

Determines if a <xref href="System.Object" data-throw-if-not-resolved="false"></xref> is equal to the current <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref>.

```csharp
public override bool Equals(object other)
```

#### Parameters

`other` [object](https://learn.microsoft.com/dotnet/api/system.object)

The object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref> objects are not equal.

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_GetHashCode"></a>GetHashCode\(\)

Gets the hash code for this <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref>.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The hash code for this <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_GetSubcommandMention_System_String___"></a>GetSubcommandMention\(params string\[\]\)

Creates a mention for a subcommand.

```csharp
public string GetSubcommandMention(params string[] name)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)\[\]

The name of the subgroup and/or subcommand.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted mention.

## Operators

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_op_Equality_DSharpPlus_Entities_DiscordApplicationCommand_DSharpPlus_Entities_DiscordApplicationCommand_"></a>operator ==\(DiscordApplicationCommand, DiscordApplicationCommand\)

Determines if two <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref> objects are equal.

```csharp
public static bool operator ==(DiscordApplicationCommand e1, DiscordApplicationCommand e2)
```

#### Parameters

`e1` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The first command object.

`e2` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The second command object.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref> objects are equal.

### <a id="DSharpPlus_Entities_DiscordApplicationCommand_op_Inequality_DSharpPlus_Entities_DiscordApplicationCommand_DSharpPlus_Entities_DiscordApplicationCommand_"></a>operator \!=\(DiscordApplicationCommand, DiscordApplicationCommand\)

Determines if two <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref> objects are not equal.

```csharp
public static bool operator !=(DiscordApplicationCommand e1, DiscordApplicationCommand e2)
```

#### Parameters

`e1` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The first command object.

`e2` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The second command object.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref> objects are not equal.


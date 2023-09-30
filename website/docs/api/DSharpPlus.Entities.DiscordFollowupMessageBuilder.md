# Class DiscordFollowupMessageBuilder

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Constructs a followup message to an interaction.

```csharp
public sealed class DiscordFollowupMessageBuilder : BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder>, IDiscordMessageBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md) ← 
[DiscordFollowupMessageBuilder](DSharpPlus.Entities.DiscordFollowupMessageBuilder.md)

###### Implements

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

###### Inherited Members

[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.Content](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Content), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.Flags](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Flags), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.SuppressNotifications\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_SuppressNotifications), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.IsTTS](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_IsTTS), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.Embeds](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Embeds), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.Files](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Files), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.Mentions](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Mentions), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.Components](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Components), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.WithContent\(string\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_WithContent\_System\_String\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.AddComponents\(params DiscordComponent\[\]\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddComponents\_DSharpPlus\_Entities\_DiscordComponent\_\_\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.AddComponents\(IEnumerable<DiscordActionRowComponent\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddComponents\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordActionRowComponent\_\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.AddComponents\(IEnumerable<DiscordComponent\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddComponents\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordComponent\_\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.WithTTS\(bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_WithTTS\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.AddEmbed\(DiscordEmbed\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddEmbed\_DSharpPlus\_Entities\_DiscordEmbed\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.AddEmbeds\(IEnumerable<DiscordEmbed\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddEmbeds\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordEmbed\_\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.AddFile\(string, Stream, bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_String\_System\_IO\_Stream\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.AddFile\(FileStream, bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_IO\_FileStream\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.AddFiles\(IDictionary<string, Stream\>, bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFiles\_System\_Collections\_Generic\_IDictionary\_System\_String\_System\_IO\_Stream\_\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.AddFile\(string, Stream, AddFileOptions\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_String\_System\_IO\_Stream\_DSharpPlus\_Entities\_AddFileOptions\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.AddFile\(FileStream, AddFileOptions\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_IO\_FileStream\_DSharpPlus\_Entities\_AddFileOptions\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.AddFiles\(IDictionary<string, Stream\>, AddFileOptions\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFiles\_System\_Collections\_Generic\_IDictionary\_System\_String\_System\_IO\_Stream\_\_DSharpPlus\_Entities\_AddFileOptions\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.AddFiles\(IEnumerable<DiscordMessageFile\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFiles\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordMessageFile\_\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.AddMention\(IMention\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddMention\_DSharpPlus\_Entities\_IMention\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.AddMentions\(IEnumerable<IMention\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddMentions\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_IMention\_\_), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.ClearComponents\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_ClearComponents), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.Clear\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Clear), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.Dispose\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Dispose), 
[BaseDiscordMessageBuilder<DiscordFollowupMessageBuilder\>.DisposeAsync\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_DisposeAsync)

## Constructors

### <a id="DSharpPlus_Entities_DiscordFollowupMessageBuilder__ctor"></a>DiscordFollowupMessageBuilder\(\)

Constructs a new followup message builder

```csharp
public DiscordFollowupMessageBuilder()
```

### <a id="DSharpPlus_Entities_DiscordFollowupMessageBuilder__ctor_DSharpPlus_Entities_DiscordFollowupMessageBuilder_"></a>DiscordFollowupMessageBuilder\(DiscordFollowupMessageBuilder\)

```csharp
public DiscordFollowupMessageBuilder(DiscordFollowupMessageBuilder builder)
```

#### Parameters

`builder` [DiscordFollowupMessageBuilder](DSharpPlus.Entities.DiscordFollowupMessageBuilder.md)

### <a id="DSharpPlus_Entities_DiscordFollowupMessageBuilder__ctor_DSharpPlus_Entities_IDiscordMessageBuilder_"></a>DiscordFollowupMessageBuilder\(IDiscordMessageBuilder\)

Copies the common properties from the passed builder.

```csharp
public DiscordFollowupMessageBuilder(IDiscordMessageBuilder builder)
```

#### Parameters

`builder` [IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

The builder to copy.

## Properties

### <a id="DSharpPlus_Entities_DiscordFollowupMessageBuilder_IsEphemeral"></a>IsEphemeral

Whether this followup message should be ephemeral.

```csharp
public bool IsEphemeral { get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

## Methods

### <a id="DSharpPlus_Entities_DiscordFollowupMessageBuilder_AsEphemeral_System_Boolean_"></a>AsEphemeral\(bool\)

Sets the followup message to be ephemeral.

```csharp
public DiscordFollowupMessageBuilder AsEphemeral(bool ephemeral = true)
```

#### Parameters

`ephemeral` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Ephemeral.

#### Returns

[DiscordFollowupMessageBuilder](DSharpPlus.Entities.DiscordFollowupMessageBuilder.md)

The builder to chain calls with.

### <a id="DSharpPlus_Entities_DiscordFollowupMessageBuilder_Clear"></a>Clear\(\)

Allows for clearing the Followup Message builder so that it can be used again to send a new message.

```csharp
public override void Clear()
```


# Class DiscordInteractionResponseBuilder

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Constructs an interaction response.

```csharp
public sealed class DiscordInteractionResponseBuilder : BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder>, IDiscordMessageBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md) ← 
[DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

###### Implements

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

###### Inherited Members

[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.Content](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Content), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.Flags](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Flags), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.SuppressNotifications\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_SuppressNotifications), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.IsTTS](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_IsTTS), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.Embeds](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Embeds), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.Files](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Files), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.Mentions](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Mentions), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.Components](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Components), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.WithContent\(string\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_WithContent\_System\_String\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.AddComponents\(params DiscordComponent\[\]\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddComponents\_DSharpPlus\_Entities\_DiscordComponent\_\_\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.AddComponents\(IEnumerable<DiscordActionRowComponent\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddComponents\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordActionRowComponent\_\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.AddComponents\(IEnumerable<DiscordComponent\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddComponents\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordComponent\_\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.WithTTS\(bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_WithTTS\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.AddEmbed\(DiscordEmbed\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddEmbed\_DSharpPlus\_Entities\_DiscordEmbed\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.AddEmbeds\(IEnumerable<DiscordEmbed\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddEmbeds\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordEmbed\_\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.AddFile\(string, Stream, bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_String\_System\_IO\_Stream\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.AddFile\(FileStream, bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_IO\_FileStream\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.AddFiles\(IDictionary<string, Stream\>, bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFiles\_System\_Collections\_Generic\_IDictionary\_System\_String\_System\_IO\_Stream\_\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.AddFile\(string, Stream, AddFileOptions\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_String\_System\_IO\_Stream\_DSharpPlus\_Entities\_AddFileOptions\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.AddFile\(FileStream, AddFileOptions\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_IO\_FileStream\_DSharpPlus\_Entities\_AddFileOptions\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.AddFiles\(IDictionary<string, Stream\>, AddFileOptions\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFiles\_System\_Collections\_Generic\_IDictionary\_System\_String\_System\_IO\_Stream\_\_DSharpPlus\_Entities\_AddFileOptions\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.AddFiles\(IEnumerable<DiscordMessageFile\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFiles\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordMessageFile\_\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.AddMention\(IMention\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddMention\_DSharpPlus\_Entities\_IMention\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.AddMentions\(IEnumerable<IMention\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddMentions\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_IMention\_\_), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.ClearComponents\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_ClearComponents), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.Clear\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Clear), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.Dispose\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Dispose), 
[BaseDiscordMessageBuilder<DiscordInteractionResponseBuilder\>.DisposeAsync\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_DisposeAsync)

## Constructors

### <a id="DSharpPlus_Entities_DiscordInteractionResponseBuilder__ctor"></a>DiscordInteractionResponseBuilder\(\)

Constructs a new empty interaction response builder.

```csharp
public DiscordInteractionResponseBuilder()
```

### <a id="DSharpPlus_Entities_DiscordInteractionResponseBuilder__ctor_DSharpPlus_Entities_IDiscordMessageBuilder_"></a>DiscordInteractionResponseBuilder\(IDiscordMessageBuilder\)

Copies the common properties from the passed builder.

```csharp
public DiscordInteractionResponseBuilder(IDiscordMessageBuilder builder)
```

#### Parameters

`builder` [IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

The builder to copy.

### <a id="DSharpPlus_Entities_DiscordInteractionResponseBuilder__ctor_DSharpPlus_Entities_DiscordInteractionResponseBuilder_"></a>DiscordInteractionResponseBuilder\(DiscordInteractionResponseBuilder\)

Constructs a new interaction response builder based on the passed builder.

```csharp
public DiscordInteractionResponseBuilder(DiscordInteractionResponseBuilder builder)
```

#### Parameters

`builder` [DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

The builder to copy.

## Properties

### <a id="DSharpPlus_Entities_DiscordInteractionResponseBuilder_Choices"></a>Choices

The choices to send on this interaction response. Mutually exclusive with content, embed, and components.

```csharp
public IReadOnlyList<DiscordAutoCompleteChoice> Choices { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordAutoCompleteChoice](DSharpPlus.Entities.DiscordAutoCompleteChoice.md)\>

### <a id="DSharpPlus_Entities_DiscordInteractionResponseBuilder_CustomId"></a>CustomId

The custom id to send with this interaction response. Only applicable when creating a modal.

```csharp
public string CustomId { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInteractionResponseBuilder_IsEphemeral"></a>IsEphemeral

Whether this interaction response should be ephemeral.

```csharp
public bool IsEphemeral { get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordInteractionResponseBuilder_Title"></a>Title

The title to send with this interaction response. Only applicable when creating a modal.

```csharp
public string Title { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="DSharpPlus_Entities_DiscordInteractionResponseBuilder_AddAutoCompleteChoice_DSharpPlus_Entities_DiscordAutoCompleteChoice_"></a>AddAutoCompleteChoice\(DiscordAutoCompleteChoice\)

Adds a single auto-complete choice to the builder.

```csharp
public DiscordInteractionResponseBuilder AddAutoCompleteChoice(DiscordAutoCompleteChoice choice)
```

#### Parameters

`choice` [DiscordAutoCompleteChoice](DSharpPlus.Entities.DiscordAutoCompleteChoice.md)

The choice to add.

#### Returns

[DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

The current builder to chain calls with.

### <a id="DSharpPlus_Entities_DiscordInteractionResponseBuilder_AddAutoCompleteChoices_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAutoCompleteChoice__"></a>AddAutoCompleteChoices\(IEnumerable<DiscordAutoCompleteChoice\>\)

Adds auto-complete choices to the builder.

```csharp
public DiscordInteractionResponseBuilder AddAutoCompleteChoices(IEnumerable<DiscordAutoCompleteChoice> choices)
```

#### Parameters

`choices` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAutoCompleteChoice](DSharpPlus.Entities.DiscordAutoCompleteChoice.md)\>

The choices to add.

#### Returns

[DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

The current builder to chain calls with.

### <a id="DSharpPlus_Entities_DiscordInteractionResponseBuilder_AddAutoCompleteChoices_DSharpPlus_Entities_DiscordAutoCompleteChoice___"></a>AddAutoCompleteChoices\(params DiscordAutoCompleteChoice\[\]\)

Adds auto-complete choices to the builder.

```csharp
public DiscordInteractionResponseBuilder AddAutoCompleteChoices(params DiscordAutoCompleteChoice[] choices)
```

#### Parameters

`choices` [DiscordAutoCompleteChoice](DSharpPlus.Entities.DiscordAutoCompleteChoice.md)\[\]

The choices to add.

#### Returns

[DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

The current builder to chain calls with.

### <a id="DSharpPlus_Entities_DiscordInteractionResponseBuilder_AsEphemeral_System_Boolean_"></a>AsEphemeral\(bool\)

Sets the interaction response to be ephemeral.

```csharp
public DiscordInteractionResponseBuilder AsEphemeral(bool ephemeral = true)
```

#### Parameters

`ephemeral` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Ephemeral.

#### Returns

[DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

### <a id="DSharpPlus_Entities_DiscordInteractionResponseBuilder_Clear"></a>Clear\(\)

Allows for clearing the Interaction Response Builder so that it can be used again to send a new response.

```csharp
public override void Clear()
```

### <a id="DSharpPlus_Entities_DiscordInteractionResponseBuilder_WithCustomId_System_String_"></a>WithCustomId\(string\)

If responding with a modal, sets the custom id for the modal.

```csharp
public DiscordInteractionResponseBuilder WithCustomId(string id)
```

#### Parameters

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The custom id of the modal.

#### Returns

[DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

### <a id="DSharpPlus_Entities_DiscordInteractionResponseBuilder_WithTitle_System_String_"></a>WithTitle\(string\)

If responding with a modal, sets the title of the modal.

```csharp
public DiscordInteractionResponseBuilder WithTitle(string title)
```

#### Parameters

`title` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

[DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)


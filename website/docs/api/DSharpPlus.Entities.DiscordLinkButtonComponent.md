# Class DiscordLinkButtonComponent

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a link button. Clicking a link button does not send an interaction.

```csharp
public class DiscordLinkButtonComponent : DiscordComponent
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordComponent](DSharpPlus.Entities.DiscordComponent.md) ← 
[DiscordLinkButtonComponent](DSharpPlus.Entities.DiscordLinkButtonComponent.md)

###### Inherited Members

[DiscordComponent.Type](DSharpPlus.Entities.DiscordComponent.md\#DSharpPlus\_Entities\_DiscordComponent\_Type), 
[DiscordComponent.CustomId](DSharpPlus.Entities.DiscordComponent.md\#DSharpPlus\_Entities\_DiscordComponent\_CustomId)

## Constructors

### <a id="DSharpPlus_Entities_DiscordLinkButtonComponent__ctor_System_String_System_String_System_Boolean_DSharpPlus_Entities_DiscordComponentEmoji_"></a>DiscordLinkButtonComponent\(string, string, bool, DiscordComponentEmoji\)

Constructs a new <xref href="DSharpPlus.Entities.DiscordLinkButtonComponent" data-throw-if-not-resolved="false"></xref>. This type of button does not send back and interaction when pressed.

```csharp
public DiscordLinkButtonComponent(string url, string label, bool disabled = false, DiscordComponentEmoji emoji = null)
```

#### Parameters

`url` [string](https://learn.microsoft.com/dotnet/api/system.string)

The url to set the button to.

`label` [string](https://learn.microsoft.com/dotnet/api/system.string)

The text to display on the button. Can be left blank if <code class="paramref">emoji</code> is set.

`disabled` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether or not this button can be pressed.

`emoji` [DiscordComponentEmoji](DSharpPlus.Entities.DiscordComponentEmoji.md)

The emoji to set with this button. This is required if <code class="paramref">label</code> is null or empty.

## Properties

### <a id="DSharpPlus_Entities_DiscordLinkButtonComponent_Disabled"></a>Disabled

Whether this button can be pressed.

```csharp
[JsonProperty("disabled", NullValueHandling = NullValueHandling.Ignore)]
public bool Disabled { get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordLinkButtonComponent_Emoji"></a>Emoji

The emoji to add to the button. Can be used in conjunction with a label, or as standalone. Must be added if label is not specified.

```csharp
[JsonProperty("emoji", NullValueHandling = NullValueHandling.Ignore)]
public DiscordComponentEmoji Emoji { get; set; }
```

#### Property Value

[DiscordComponentEmoji](DSharpPlus.Entities.DiscordComponentEmoji.md)

### <a id="DSharpPlus_Entities_DiscordLinkButtonComponent_Label"></a>Label

The text to add to this button. If this is not specified, <xref href="DSharpPlus.Entities.DiscordLinkButtonComponent.Emoji" data-throw-if-not-resolved="false"></xref> must be.

```csharp
[JsonProperty("label", NullValueHandling = NullValueHandling.Ignore)]
public string Label { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordLinkButtonComponent_Url"></a>Url

The url to open when pressing this button.

```csharp
[JsonProperty("url", NullValueHandling = NullValueHandling.Ignore)]
public string Url { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)


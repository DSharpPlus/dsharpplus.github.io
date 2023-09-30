# Class DiscordButtonComponent

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a button that can be pressed. Fires <xref href="DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs" data-throw-if-not-resolved="false"></xref> when pressed.

```csharp
public sealed class DiscordButtonComponent : DiscordComponent
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordComponent](DSharpPlus.Entities.DiscordComponent.md) ← 
[DiscordButtonComponent](DSharpPlus.Entities.DiscordButtonComponent.md)

###### Inherited Members

[DiscordComponent.Type](DSharpPlus.Entities.DiscordComponent.md\#DSharpPlus\_Entities\_DiscordComponent\_Type), 
[DiscordComponent.CustomId](DSharpPlus.Entities.DiscordComponent.md\#DSharpPlus\_Entities\_DiscordComponent\_CustomId)

## Constructors

### <a id="DSharpPlus_Entities_DiscordButtonComponent__ctor_DSharpPlus_Entities_DiscordButtonComponent_"></a>DiscordButtonComponent\(DiscordButtonComponent\)

Constucts a new button based on another button.

```csharp
public DiscordButtonComponent(DiscordButtonComponent other)
```

#### Parameters

`other` [DiscordButtonComponent](DSharpPlus.Entities.DiscordButtonComponent.md)

The button to copy.

### <a id="DSharpPlus_Entities_DiscordButtonComponent__ctor_DSharpPlus_ButtonStyle_System_String_System_String_System_Boolean_DSharpPlus_Entities_DiscordComponentEmoji_"></a>DiscordButtonComponent\(ButtonStyle, string, string, bool, DiscordComponentEmoji\)

Constructs a new button with the specified options.

```csharp
public DiscordButtonComponent(ButtonStyle style, string customId, string label, bool disabled = false, DiscordComponentEmoji emoji = null)
```

#### Parameters

`style` [ButtonStyle](DSharpPlus.ButtonStyle.md)

The style/color of the button.

`customId` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id to assign to the button. This is sent back when a user presses it.

`label` [string](https://learn.microsoft.com/dotnet/api/system.string)

The text to display on the button, up to 80 characters. Can be left blank if <code class="paramref">emoji</code>is set.

`disabled` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this button should be initialized as being disabled. User sees a greyed out button that cannot be interacted with.

`emoji` [DiscordComponentEmoji](DSharpPlus.Entities.DiscordComponentEmoji.md)

The emoji to add to the button. This is required if <code class="paramref">label</code> is empty or null.

## Properties

### <a id="DSharpPlus_Entities_DiscordButtonComponent_Disabled"></a>Disabled

Whether this button can be pressed.

```csharp
[JsonProperty("disabled", NullValueHandling = NullValueHandling.Ignore)]
public bool Disabled { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordButtonComponent_Emoji"></a>Emoji

The emoji to add to the button. Can be used in conjunction with a label, or as standalone. Must be added if label is not specified.

```csharp
[JsonProperty("emoji", NullValueHandling = NullValueHandling.Ignore)]
public DiscordComponentEmoji Emoji { get; }
```

#### Property Value

[DiscordComponentEmoji](DSharpPlus.Entities.DiscordComponentEmoji.md)

### <a id="DSharpPlus_Entities_DiscordButtonComponent_Label"></a>Label

The text to apply to the button. If this is not specified <xref href="DSharpPlus.Entities.DiscordButtonComponent.Emoji" data-throw-if-not-resolved="false"></xref> becomes required.

```csharp
[JsonProperty("label", NullValueHandling = NullValueHandling.Ignore)]
public string Label { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordButtonComponent_Style"></a>Style

The style of the button.

```csharp
[JsonProperty("style", NullValueHandling = NullValueHandling.Ignore)]
public ButtonStyle Style { get; }
```

#### Property Value

[ButtonStyle](DSharpPlus.ButtonStyle.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordButtonComponent_Disable"></a>Disable\(\)

Disables this component.

```csharp
public DiscordButtonComponent Disable()
```

#### Returns

[DiscordButtonComponent](DSharpPlus.Entities.DiscordButtonComponent.md)

The current component.

### <a id="DSharpPlus_Entities_DiscordButtonComponent_Enable"></a>Enable\(\)

Enables this component if it was disabled before.

```csharp
public DiscordButtonComponent Enable()
```

#### Returns

[DiscordButtonComponent](DSharpPlus.Entities.DiscordButtonComponent.md)

The current component.


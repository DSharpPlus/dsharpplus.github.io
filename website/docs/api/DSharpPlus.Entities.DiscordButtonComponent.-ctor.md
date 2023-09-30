# Constructor DiscordButtonComponent

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordButtonComponent__ctor_DSharpPlus_Entities_DiscordButtonComponent_"></a>DiscordButtonComponent\(DiscordButtonComponent\)

Constucts a new button based on another button.

```csharp
public DiscordButtonComponent(DiscordButtonComponent other)
```

### Parameters

`other` [DiscordButtonComponent](DSharpPlus.Entities.DiscordButtonComponent.md)

The button to copy.

## <a id="DSharpPlus_Entities_DiscordButtonComponent__ctor_DSharpPlus_ButtonStyle_System_String_System_String_System_Boolean_DSharpPlus_Entities_DiscordComponentEmoji_"></a>DiscordButtonComponent\(ButtonStyle, string, string, bool, DiscordComponentEmoji\)

Constructs a new button with the specified options.

```csharp
public DiscordButtonComponent(ButtonStyle style, string customId, string label, bool disabled = false, DiscordComponentEmoji emoji = null)
```

### Parameters

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


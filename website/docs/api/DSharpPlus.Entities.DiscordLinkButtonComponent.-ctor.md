# Constructor DiscordLinkButtonComponent

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordLinkButtonComponent__ctor_System_String_System_String_System_Boolean_DSharpPlus_Entities_DiscordComponentEmoji_"></a>DiscordLinkButtonComponent\(string, string, bool, DiscordComponentEmoji\)

Constructs a new <xref href="DSharpPlus.Entities.DiscordLinkButtonComponent" data-throw-if-not-resolved="false"></xref>. This type of button does not send back and interaction when pressed.

```csharp
public DiscordLinkButtonComponent(string url, string label, bool disabled = false, DiscordComponentEmoji emoji = null)
```

### Parameters

`url` [string](https://learn.microsoft.com/dotnet/api/system.string)

The url to set the button to.

`label` [string](https://learn.microsoft.com/dotnet/api/system.string)

The text to display on the button. Can be left blank if <code class="paramref">emoji</code> is set.

`disabled` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether or not this button can be pressed.

`emoji` [DiscordComponentEmoji](DSharpPlus.Entities.DiscordComponentEmoji.md)

The emoji to set with this button. This is required if <code class="paramref">label</code> is null or empty.


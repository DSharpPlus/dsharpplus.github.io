# Method ModifyWidgetSettingsAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_ModifyWidgetSettingsAsync_System_Nullable_System_Boolean__DSharpPlus_Entities_DiscordChannel_System_String_"></a>ModifyWidgetSettingsAsync\(bool?, DiscordChannel, string\)

Modifies the guild's widget settings

```csharp
public Task<DiscordWidgetSettings> ModifyWidgetSettingsAsync(bool? isEnabled = null, DiscordChannel channel = null, string reason = null)
```

### Parameters

`isEnabled` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

If the widget is enabled or not

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Widget channel

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason the widget settings were modified

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWidgetSettings](DSharpPlus.Entities.DiscordWidgetSettings.md)\>

The newly modified widget settings


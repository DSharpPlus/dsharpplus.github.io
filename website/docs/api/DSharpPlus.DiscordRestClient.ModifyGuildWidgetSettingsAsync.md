# Method ModifyGuildWidgetSettingsAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyGuildWidgetSettingsAsync_System_UInt64_System_Nullable_System_Boolean__System_Nullable_System_UInt64__System_String_"></a>ModifyGuildWidgetSettingsAsync\(ulong, bool?, ulong?, string\)

Modifies a guild's widget settings

```csharp
public Task<DiscordWidgetSettings> ModifyGuildWidgetSettingsAsync(ulong guild_id, bool? enabled = null, ulong? channel_id = null, string reason = null)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`enabled` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

If the widget is enabled or not

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Widget channel ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason the widget settings were modified

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWidgetSettings](DSharpPlus.Entities.DiscordWidgetSettings.md)\>


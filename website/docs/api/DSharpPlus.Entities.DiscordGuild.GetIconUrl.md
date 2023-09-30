# Method GetIconUrl

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetIconUrl_DSharpPlus_ImageFormat_System_UInt16_"></a>GetIconUrl\(ImageFormat, ushort\)

Gets guild's icon URL, in requested format and size.

```csharp
public string GetIconUrl(ImageFormat imageFormat, ushort imageSize = 1024)
```

### Parameters

`imageFormat` [ImageFormat](DSharpPlus.ImageFormat.md)

The image format of the icon to get.

`imageSize` [ushort](https://learn.microsoft.com/dotnet/api/system.uint16)

The maximum size of the icon. Must be a power of two, minimum 16, maximum 4096.

### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

The URL of the guild's icon.


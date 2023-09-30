# Method GetAvatarUrl

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordUser_GetAvatarUrl_DSharpPlus_ImageFormat_System_UInt16_"></a>GetAvatarUrl\(ImageFormat, ushort\)

Gets the user's avatar URL, in requested format and size.

```csharp
public string GetAvatarUrl(ImageFormat imageFormat, ushort imageSize = 1024)
```

### Parameters

`imageFormat` [ImageFormat](DSharpPlus.ImageFormat.md)

The image format of the avatar to get.

`imageSize` [ushort](https://learn.microsoft.com/dotnet/api/system.uint16)

The maximum size of the avatar. Must be a power of two, minimum 16, maximum 4096.

### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

The URL of the user's avatar.


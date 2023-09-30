# Method GetAvatarUrl

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordApplication_GetAvatarUrl_DSharpPlus_ImageFormat_System_UInt16_"></a>GetAvatarUrl\(ImageFormat, ushort\)

Gets the application's cover image URL, in requested format and size.

```csharp
public string GetAvatarUrl(ImageFormat fmt, ushort size = 1024)
```

### Parameters

`fmt` [ImageFormat](DSharpPlus.ImageFormat.md)

Format of the image to get.

`size` [ushort](https://learn.microsoft.com/dotnet/api/system.uint16)

Maximum size of the cover image. Must be a power of two, minimum 16, maximum 2048.

### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

URL of the application's cover image.


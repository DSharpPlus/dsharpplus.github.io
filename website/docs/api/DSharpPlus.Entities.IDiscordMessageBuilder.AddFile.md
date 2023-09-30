# Method AddFile

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddFile_System_String_System_IO_Stream_System_Boolean_"></a>AddFile\(string, Stream, bool\)

Attaches a file to this message.

```csharp
IDiscordMessageBuilder AddFile(string fileName, Stream stream, bool resetStream = false)
```

### Parameters

`fileName` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the file to attach.

`stream` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

Stream containing said file's contents.

`resetStream` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to reset the stream to position 0 after sending.

### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

## <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddFile_System_IO_FileStream_System_Boolean_"></a>AddFile\(FileStream, bool\)

Attaches a file to this message.

```csharp
IDiscordMessageBuilder AddFile(FileStream stream, bool resetStream = false)
```

### Parameters

`stream` [FileStream](https://learn.microsoft.com/dotnet/api/system.io.filestream)

FileStream pointing to the file to attach.

`resetStream` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to reset the stream position to 0 after sending.

### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

## <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddFile_System_String_System_IO_Stream_DSharpPlus_Entities_AddFileOptions_"></a>AddFile\(string, Stream, AddFileOptions\)

Attaches a file to this message.

```csharp
IDiscordMessageBuilder AddFile(string fileName, Stream stream, AddFileOptions fileOptions)
```

### Parameters

`fileName` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the file to attach.

`stream` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

Stream containing said file's contents.

`fileOptions` [AddFileOptions](DSharpPlus.Entities.AddFileOptions.md)

Additional flags for the handling of the file stream.

### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

## <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddFile_System_IO_FileStream_DSharpPlus_Entities_AddFileOptions_"></a>AddFile\(FileStream, AddFileOptions\)

Attaches a file to this message.

```csharp
IDiscordMessageBuilder AddFile(FileStream stream, AddFileOptions fileOptions)
```

### Parameters

`stream` [FileStream](https://learn.microsoft.com/dotnet/api/system.io.filestream)

FileStream pointing to the file to attach.

`fileOptions` [AddFileOptions](DSharpPlus.Entities.AddFileOptions.md)

Additional flags for the handling of the file stream.

### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)


# Method AddFile

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddFile_System_String_System_IO_Stream_System_Boolean_"></a>AddFile\(string, Stream, bool\)

Sets if the message has files to be sent.

```csharp
public T AddFile(string fileName, Stream stream, bool resetStreamPosition = false)
```

### Parameters

`fileName` [string](https://learn.microsoft.com/dotnet/api/system.string)

The fileName that the file should be sent as.

`stream` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The Stream to the file.

`resetStreamPosition` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Tells the API Client to reset the stream position to what it was after the file is sent.

### Returns

T

The current builder to be chained.

## <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddFile_System_IO_FileStream_System_Boolean_"></a>AddFile\(FileStream, bool\)

Sets if the message has files to be sent.

```csharp
public T AddFile(FileStream stream, bool resetStreamPosition = false)
```

### Parameters

`stream` [FileStream](https://learn.microsoft.com/dotnet/api/system.io.filestream)

The Stream to the file.

`resetStreamPosition` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Tells the API Client to reset the stream position to what it was after the file is sent.

### Returns

T

The current builder to be chained.

## <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddFile_System_String_System_IO_Stream_DSharpPlus_Entities_AddFileOptions_"></a>AddFile\(string, Stream, AddFileOptions\)

Attaches a file to this message.

```csharp
public T AddFile(string fileName, Stream stream, AddFileOptions fileOptions)
```

### Parameters

`fileName` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the file to attach.

`stream` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

Stream containing said file's contents.

`fileOptions` [AddFileOptions](DSharpPlus.Entities.AddFileOptions.md)

Additional flags for the handling of the file stream.

### Returns

T

The current builder to be chained.

## <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddFile_System_IO_FileStream_DSharpPlus_Entities_AddFileOptions_"></a>AddFile\(FileStream, AddFileOptions\)

Attaches a file to this message.

```csharp
public T AddFile(FileStream stream, AddFileOptions fileOptions)
```

### Parameters

`stream` [FileStream](https://learn.microsoft.com/dotnet/api/system.io.filestream)

FileStream pointing to the file to attach.

`fileOptions` [AddFileOptions](DSharpPlus.Entities.AddFileOptions.md)

Additional flags for the handling of the file stream.

### Returns

T

The current builder to be chained.


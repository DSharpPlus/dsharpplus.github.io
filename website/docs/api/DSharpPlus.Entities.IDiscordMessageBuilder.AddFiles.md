# Method AddFiles

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddFiles_System_Collections_Generic_IDictionary_System_String_System_IO_Stream__System_Boolean_"></a>AddFiles\(IDictionary<string, Stream\>, bool\)

Attaches multiple files to this message.

```csharp
IDiscordMessageBuilder AddFiles(IDictionary<string, Stream> files, bool resetStreams = false)
```

### Parameters

`files` [IDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.idictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

Dictionary of files to add, where <xref href="System.String" data-throw-if-not-resolved="false"></xref> is a file name and <xref href="System.IO.Stream" data-throw-if-not-resolved="false"></xref> is a stream containing the file's contents.

`resetStreams` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to reset all stream positions to 0 after sending.

### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

## <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddFiles_System_Collections_Generic_IDictionary_System_String_System_IO_Stream__DSharpPlus_Entities_AddFileOptions_"></a>AddFiles\(IDictionary<string, Stream\>, AddFileOptions\)

Attaches multiple files to this message.

```csharp
IDiscordMessageBuilder AddFiles(IDictionary<string, Stream> files, AddFileOptions fileOptions)
```

### Parameters

`files` [IDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.idictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

Dictionary of files to add, where <xref href="System.String" data-throw-if-not-resolved="false"></xref> is a file name and <xref href="System.IO.Stream" data-throw-if-not-resolved="false"></xref> is a stream containing the file's contents.

`fileOptions` [AddFileOptions](DSharpPlus.Entities.AddFileOptions.md)

Additional flags for the handling of the file streams.

### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

## <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddFiles_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordMessageFile__"></a>AddFiles\(IEnumerable<DiscordMessageFile\>\)

Attaches previously used files to this file stream.

```csharp
IDiscordMessageBuilder AddFiles(IEnumerable<DiscordMessageFile> files)
```

### Parameters

`files` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordMessageFile](DSharpPlus.Entities.DiscordMessageFile.md)\>

Previously attached files to reattach

### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)


# Method AddFiles

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddFiles_System_Collections_Generic_IDictionary_System_String_System_IO_Stream__System_Boolean_"></a>AddFiles\(IDictionary<string, Stream\>, bool\)

Sets if the message has files to be sent.

```csharp
public T AddFiles(IDictionary<string, Stream> files, bool resetStreamPosition = false)
```

### Parameters

`files` [IDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.idictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

The Files that should be sent.

`resetStreamPosition` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Tells the API Client to reset the stream position to what it was after the file is sent.

### Returns

T

The current builder to be chained.

## <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddFiles_System_Collections_Generic_IDictionary_System_String_System_IO_Stream__DSharpPlus_Entities_AddFileOptions_"></a>AddFiles\(IDictionary<string, Stream\>, AddFileOptions\)

Attaches multiple files to this message.

```csharp
public T AddFiles(IDictionary<string, Stream> files, AddFileOptions fileOptions)
```

### Parameters

`files` [IDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.idictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

Dictionary of files to add, where <xref href="System.String" data-throw-if-not-resolved="false"></xref> is a file name and <xref href="System.IO.Stream" data-throw-if-not-resolved="false"></xref> is a stream containing the file's contents.

`fileOptions` [AddFileOptions](DSharpPlus.Entities.AddFileOptions.md)

Additional flags for the handling of the file streams.

### Returns

T

The current builder to be chained.

## <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddFiles_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordMessageFile__"></a>AddFiles\(IEnumerable<DiscordMessageFile\>\)

```csharp
public T AddFiles(IEnumerable<DiscordMessageFile> files)
```

### Parameters

`files` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordMessageFile](DSharpPlus.Entities.DiscordMessageFile.md)\>

### Returns

T


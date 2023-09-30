# Class ImageTool

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Tool to detect image formats and convert from binary data to base64 strings.

```csharp
public sealed class ImageTool
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ImageTool](DSharpPlus.ImageTool.md)

## Constructors

### <a id="DSharpPlus_ImageTool__ctor_System_IO_Stream_"></a>ImageTool\(Stream\)

Creates a new image tool from given stream.

```csharp
public ImageTool(Stream stream)
```

#### Parameters

`stream` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

Stream to work with.

## Properties

### <a id="DSharpPlus_ImageTool_SourceStream"></a>SourceStream

Gets the stream this tool is operating on.

```csharp
public Stream SourceStream { get; }
```

#### Property Value

[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

## Methods

### <a id="DSharpPlus_ImageTool_Dispose"></a>Dispose\(\)

Disposes this image tool.

```csharp
public void Dispose()
```

### <a id="DSharpPlus_ImageTool_GetBase64"></a>GetBase64\(\)

Converts this image into base64 data format string.

```csharp
public string GetBase64()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Data-scheme base64 string.

### <a id="DSharpPlus_ImageTool_GetFormat"></a>GetFormat\(\)

Detects the format of this image.

```csharp
public ImageFormat GetFormat()
```

#### Returns

[ImageFormat](DSharpPlus.ImageFormat.md)

Detected format.


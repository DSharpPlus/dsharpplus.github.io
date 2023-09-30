# Enum AddFileOptions

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Additional flags for files added to a message builder.

```csharp
[Flags]
public enum AddFileOptions
```

###### Extension Methods

[ExtensionMethods.GetName<AddFileOptions\>\(AddFileOptions\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`CloseStream = 2` 

Closes the stream upon disposal of the message builder.

`CopyStream = 4` 

Immediately reads the stream to completion and copies its contents to an in-memory stream.

`None = 0` 

No additional behavior. The stream will read to completion and is left at that position after sending.

`ResetStream = 1` 

Resets the stream to its original position after sending.


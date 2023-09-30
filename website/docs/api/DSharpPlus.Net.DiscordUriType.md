# Enum DiscordUriType

Namespace: [DSharpPlus.Net](DSharpPlus.Net.md)  
Assembly: DSharpPlus.dll

```csharp
public enum DiscordUriType : byte
```

###### Extension Methods

[ExtensionMethods.GetName<DiscordUriType\>\(DiscordUriType\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`NonStandard = 1` 

Represents a URI that does not conform to RFC 3986, meaning it's stored internally as a plain string and
should be treated as one.

`Standard = 0` 

Represents a URI that conforms to RFC 3986, meaning it's stored internally as a <xref href="System.Uri" data-throw-if-not-resolved="false"></xref> and will
contain a trailing slash after the domain name.


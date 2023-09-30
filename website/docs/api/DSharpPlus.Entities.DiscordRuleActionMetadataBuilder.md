# Class DiscordRuleActionMetadataBuilder

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Constructs auto-moderation rule action metadata.

```csharp
public class DiscordRuleActionMetadataBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordRuleActionMetadataBuilder](DSharpPlus.Entities.DiscordRuleActionMetadataBuilder.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordRuleActionMetadataBuilder_ChannelId"></a>ChannelId

Sets the channel which the blocked content should be logged.

```csharp
public ulong ChannelId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordRuleActionMetadataBuilder_CustomMessage"></a>CustomMessage

Gets the message that will be shown on the user screen whenever the message is blocked.

```csharp
public string? CustomMessage { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_Entities_DiscordRuleActionMetadataBuilder_DurationSeconds"></a>DurationSeconds

Sets the timeout duration in seconds.

```csharp
public uint DurationSeconds { get; }
```

#### Property Value

[uint](https://learn.microsoft.com/dotnet/api/system.uint32)

## Methods

### <a id="DSharpPlus_Entities_DiscordRuleActionMetadataBuilder_Build"></a>Build\(\)

Build the rule action.

```csharp
public DiscordRuleActionMetadata Build()
```

#### Returns

[DiscordRuleActionMetadata](DSharpPlus.Entities.DiscordRuleActionMetadata.md)

The built rule action.

### <a id="DSharpPlus_Entities_DiscordRuleActionMetadataBuilder_WithCustomMessage_System_String_"></a>WithCustomMessage\(string\)

Add the custom message which will be shown when the rule will be triggered.

```csharp
public DiscordRuleActionMetadataBuilder WithCustomMessage(string message)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message to show.

#### Returns

[DiscordRuleActionMetadataBuilder](DSharpPlus.Entities.DiscordRuleActionMetadataBuilder.md)

This builder.

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

### <a id="DSharpPlus_Entities_DiscordRuleActionMetadataBuilder_WithLogChannelId_System_UInt64_"></a>WithLogChannelId\(ulong\)

Add the channel id in which the blocked content will be logged.

```csharp
public DiscordRuleActionMetadataBuilder WithLogChannelId(ulong channelId)
```

#### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The channel id.

#### Returns

[DiscordRuleActionMetadataBuilder](DSharpPlus.Entities.DiscordRuleActionMetadataBuilder.md)

### <a id="DSharpPlus_Entities_DiscordRuleActionMetadataBuilder_WithTimeoutDuration_System_UInt32_"></a>WithTimeoutDuration\(uint\)

Add the timeout duration in seconds that will be applied on the member which triggered the rule.

```csharp
public DiscordRuleActionMetadataBuilder WithTimeoutDuration(uint timeoutDurationInSeconds)
```

#### Parameters

`timeoutDurationInSeconds` [uint](https://learn.microsoft.com/dotnet/api/system.uint32)

Timeout duration.

#### Returns

[DiscordRuleActionMetadataBuilder](DSharpPlus.Entities.DiscordRuleActionMetadataBuilder.md)

This builder.


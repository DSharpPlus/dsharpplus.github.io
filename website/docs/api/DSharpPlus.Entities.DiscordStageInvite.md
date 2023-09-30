# Class DiscordStageInvite

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents an invite to a stage channel.

```csharp
public class DiscordStageInvite
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordStageInvite](DSharpPlus.Entities.DiscordStageInvite.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordStageInvite_Members"></a>Members

Gets the members that are currently speaking in the stage channel.

```csharp
[JsonProperty("members")]
public IReadOnlyCollection<DiscordMember> Members { get; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

### <a id="DSharpPlus_Entities_DiscordStageInvite_ParticipantCount"></a>ParticipantCount

Gets the number of participants in the stage channel.

```csharp
[JsonProperty("participant_count")]
public int ParticipantCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordStageInvite_SpeakerCount"></a>SpeakerCount

Gets the number of speakers in the stage channel.

```csharp
[JsonProperty("speaker_count")]
public int SpeakerCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordStageInvite_Topic"></a>Topic

Gets the topic of the stage channel.

```csharp
[JsonProperty("topic")]
public string Topic { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)


# Class DiscordActivity

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a game that a user is playing.

```csharp
public sealed class DiscordActivity
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordActivity](DSharpPlus.Entities.DiscordActivity.md)

## Constructors

### <a id="DSharpPlus_Entities_DiscordActivity__ctor"></a>DiscordActivity\(\)

Creates a new, empty instance of a <xref href="DSharpPlus.Entities.DiscordActivity" data-throw-if-not-resolved="false"></xref>.

```csharp
public DiscordActivity()
```

### <a id="DSharpPlus_Entities_DiscordActivity__ctor_System_String_"></a>DiscordActivity\(string\)

Creates a new instance of a <xref href="DSharpPlus.Entities.DiscordActivity" data-throw-if-not-resolved="false"></xref> with specified name.

```csharp
public DiscordActivity(string name)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the activity.

### <a id="DSharpPlus_Entities_DiscordActivity__ctor_System_String_DSharpPlus_Entities_ActivityType_"></a>DiscordActivity\(string, ActivityType\)

Creates a new instance of a <xref href="DSharpPlus.Entities.DiscordActivity" data-throw-if-not-resolved="false"></xref> with specified name.

```csharp
public DiscordActivity(string name, ActivityType type)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the activity.

`type` [ActivityType](DSharpPlus.Entities.ActivityType.md)

Type of the activity.

## Properties

### <a id="DSharpPlus_Entities_DiscordActivity_ActivityType"></a>ActivityType

Gets or sets the activity type.

```csharp
public ActivityType ActivityType { get; set; }
```

#### Property Value

[ActivityType](DSharpPlus.Entities.ActivityType.md)

### <a id="DSharpPlus_Entities_DiscordActivity_CustomStatus"></a>CustomStatus

Gets the custom status of this activity, if present.

```csharp
public DiscordCustomStatus CustomStatus { get; }
```

#### Property Value

[DiscordCustomStatus](DSharpPlus.Entities.DiscordCustomStatus.md)

### <a id="DSharpPlus_Entities_DiscordActivity_Name"></a>Name

Gets or sets the name of user's activity.

```csharp
public string Name { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordActivity_RichPresence"></a>RichPresence

Gets the rich presence details, if present.

```csharp
public DiscordRichPresence RichPresence { get; }
```

#### Property Value

[DiscordRichPresence](DSharpPlus.Entities.DiscordRichPresence.md)

### <a id="DSharpPlus_Entities_DiscordActivity_StreamUrl"></a>StreamUrl

Gets or sets the stream URL, if applicable.

```csharp
public string StreamUrl { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)


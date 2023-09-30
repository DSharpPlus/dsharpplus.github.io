# Class GuildEditModel

Namespace: [DSharpPlus.Net.Models](DSharpPlus.Net.Models.md)  
Assembly: DSharpPlus.dll

```csharp
public class GuildEditModel : BaseEditModel
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseEditModel](DSharpPlus.Net.Models.BaseEditModel.md) ← 
[GuildEditModel](DSharpPlus.Net.Models.GuildEditModel.md)

###### Inherited Members

[BaseEditModel.AuditLogReason](DSharpPlus.Net.Models.BaseEditModel.md\#DSharpPlus\_Net\_Models\_BaseEditModel\_AuditLogReason)

## Properties

### <a id="DSharpPlus_Net_Models_GuildEditModel_AfkChannel"></a>AfkChannel

The new AFK voice channel.

```csharp
public Optional<DiscordChannel> AfkChannel { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_AfkTimeout"></a>AfkTimeout

The new AFK timeout time in seconds.

```csharp
public Optional<int> AfkTimeout { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_Banner"></a>Banner

The new banner of the guild

```csharp
public Optional<Stream> Banner { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_DefaultMessageNotifications"></a>DefaultMessageNotifications

The new guild default message notification level.

```csharp
public Optional<DefaultMessageNotifications> DefaultMessageNotifications { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DefaultMessageNotifications](DSharpPlus.Entities.DefaultMessageNotifications.md)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_Description"></a>Description

The new description of the guild

```csharp
public Optional<string> Description { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_DiscoverySplash"></a>DiscoverySplash

The new discovery splash image of the guild

```csharp
public Optional<string> DiscoverySplash { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_ExplicitContentFilter"></a>ExplicitContentFilter

The new guild explicit content filter level.

```csharp
public Optional<ExplicitContentFilter> ExplicitContentFilter { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[ExplicitContentFilter](DSharpPlus.Entities.ExplicitContentFilter.md)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_Features"></a>Features

A list of <a href="https://discord.com/developers/docs/resources/guild#guild-object-guild-features">guild features</a>

```csharp
public Optional<IEnumerable<string>> Features { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_Icon"></a>Icon

The new guild icon.

```csharp
public Optional<Stream> Icon { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_MfaLevel"></a>MfaLevel

The new guild MFA level.

```csharp
public Optional<MfaLevel> MfaLevel { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[MfaLevel](DSharpPlus.Entities.MfaLevel.md)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_Name"></a>Name

The new guild name.

```csharp
public Optional<string> Name { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_Owner"></a>Owner

The new guild owner.

```csharp
public Optional<DiscordMember> Owner { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_PreferredLocale"></a>PreferredLocale

The new guild preferred locale.

```csharp
public Optional<string> PreferredLocale { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_PublicUpdatesChannel"></a>PublicUpdatesChannel

The new guild public updates channel.

```csharp
public Optional<DiscordChannel> PublicUpdatesChannel { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_Region"></a>Region

The new guild voice region.

```csharp
public Optional<DiscordVoiceRegion> Region { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_RulesChannel"></a>RulesChannel

The new guild rules channel.

```csharp
public Optional<DiscordChannel> RulesChannel { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_Splash"></a>Splash

The new guild splash.

```csharp
public Optional<Stream> Splash { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_SystemChannel"></a>SystemChannel

The new guild system channel.

```csharp
public Optional<DiscordChannel> SystemChannel { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_SystemChannelFlags"></a>SystemChannelFlags

The new system channel flags for the guild

```csharp
public Optional<SystemChannelFlags> SystemChannelFlags { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[SystemChannelFlags](DSharpPlus.SystemChannelFlags.md)\>

### <a id="DSharpPlus_Net_Models_GuildEditModel_VerificationLevel"></a>VerificationLevel

The new guild verification level.

```csharp
public Optional<VerificationLevel> VerificationLevel { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[VerificationLevel](DSharpPlus.Entities.VerificationLevel.md)\>


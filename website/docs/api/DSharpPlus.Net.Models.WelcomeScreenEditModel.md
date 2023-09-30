# Class WelcomeScreenEditModel

Namespace: [DSharpPlus.Net.Models](DSharpPlus.Net.Models.md)  
Assembly: DSharpPlus.dll

```csharp
public class WelcomeScreenEditModel
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[WelcomeScreenEditModel](DSharpPlus.Net.Models.WelcomeScreenEditModel.md)

## Properties

### <a id="DSharpPlus_Net_Models_WelcomeScreenEditModel_Description"></a>Description

Sets the serer description shown.

```csharp
public Optional<string> Description { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Net_Models_WelcomeScreenEditModel_Enabled"></a>Enabled

Sets whether the welcome screen should be enabled.

```csharp
public Optional<bool> Enabled { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

### <a id="DSharpPlus_Net_Models_WelcomeScreenEditModel_WelcomeChannels"></a>WelcomeChannels

Sets the welcome channels.

```csharp
public Optional<IEnumerable<DiscordGuildWelcomeScreenChannel>> WelcomeChannels { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordGuildWelcomeScreenChannel](DSharpPlus.Entities.DiscordGuildWelcomeScreenChannel.md)\>\>


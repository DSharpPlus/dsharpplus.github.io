# Class MembershipScreeningEditModel

Namespace: [DSharpPlus.Net.Models](DSharpPlus.Net.Models.md)  
Assembly: DSharpPlus.dll

```csharp
public class MembershipScreeningEditModel : BaseEditModel
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseEditModel](DSharpPlus.Net.Models.BaseEditModel.md) ← 
[MembershipScreeningEditModel](DSharpPlus.Net.Models.MembershipScreeningEditModel.md)

###### Inherited Members

[BaseEditModel.AuditLogReason](DSharpPlus.Net.Models.BaseEditModel.md\#DSharpPlus\_Net\_Models\_BaseEditModel\_AuditLogReason)

## Properties

### <a id="DSharpPlus_Net_Models_MembershipScreeningEditModel_Description"></a>Description

Sets the server description shown in the membership screening form

```csharp
public Optional<string> Description { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Net_Models_MembershipScreeningEditModel_Enabled"></a>Enabled

Sets whether membership screening should be enabled for this guild

```csharp
public Optional<bool> Enabled { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

### <a id="DSharpPlus_Net_Models_MembershipScreeningEditModel_Fields"></a>Fields

Sets the fields in this membership screening form

```csharp
public Optional<DiscordGuildMembershipScreeningField[]> Fields { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordGuildMembershipScreeningField](DSharpPlus.Entities.DiscordGuildMembershipScreeningField.md)\[\]\>


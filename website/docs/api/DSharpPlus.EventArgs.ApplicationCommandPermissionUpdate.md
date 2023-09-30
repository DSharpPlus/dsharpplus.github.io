# Class ApplicationCommandPermissionUpdate

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

```csharp
public class ApplicationCommandPermissionUpdate
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ApplicationCommandPermissionUpdate](DSharpPlus.EventArgs.ApplicationCommandPermissionUpdate.md)

## Properties

### <a id="DSharpPlus_EventArgs_ApplicationCommandPermissionUpdate_Allow"></a>Allow

Whether the role/user/channel [or anyone in the channel/with the role] is allowed to use the command.

```csharp
[JsonProperty("permission")]
public bool Allow { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_EventArgs_ApplicationCommandPermissionUpdate_Id"></a>Id

The Id of the entity this permission is for.

```csharp
[JsonProperty("id")]
public ulong Id { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_EventArgs_ApplicationCommandPermissionUpdate_Type"></a>Type

```csharp
[JsonProperty("type")]
public ApplicationCommandPermissionType Type { get; }
```

#### Property Value

[ApplicationCommandPermissionType](DSharpPlus.ApplicationCommandPermissionType.md)


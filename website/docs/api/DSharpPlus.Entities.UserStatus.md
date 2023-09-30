# Enum UserStatus

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents user status.

```csharp
[JsonConverter(typeof(UserStatusConverter))]
public enum UserStatus
```

###### Extension Methods

[ExtensionMethods.GetName<UserStatus\>\(UserStatus\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`DoNotDisturb = 4` 

User asked not to be disturbed.

`Idle = 2` 

User is idle.

`Invisible = 5` 

User is invisible. They will appear as Offline to anyone but themselves.

`Offline = 0` 

User is offline.

`Online = 1` 

User is online.


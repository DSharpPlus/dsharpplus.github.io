# Enum CooldownBucketType

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Defines how are command cooldowns applied.

```csharp
public enum CooldownBucketType
```

###### Extension Methods

[ExtensionMethods.GetName<CooldownBucketType\>\(CooldownBucketType\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`Channel = 2` 

Denotes that the command will have its cooldown applied per-channel.

`Global = 0` 

Denotes that the command will have its cooldown applied globally.

`Guild = 4` 

Denotes that the command will have its cooldown applied per-guild. In DMs, this applies the cooldown per-channel.

`User = 1` 

Denotes that the command will have its cooldown applied per-user.


# Enum SlashModuleLifespan

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Represents a slash command module lifespan.

```csharp
public enum SlashModuleLifespan
```

###### Extension Methods

[ExtensionMethods.GetName<SlashModuleLifespan\>\(SlashModuleLifespan\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`Scoped = 0` 

Whether this module should be initiated every time a command is run, with dependencies injected from a scope.

`Singleton = 2` 

Whether this module should be initiated at startup.

`Transient = 1` 

Whether this module should be initiated every time a command is run.


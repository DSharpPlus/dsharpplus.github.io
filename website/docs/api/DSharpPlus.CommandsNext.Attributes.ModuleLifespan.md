# Enum ModuleLifespan

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Defines lifespan of a command module.

```csharp
public enum ModuleLifespan
```

###### Extension Methods

[ExtensionMethods.GetName<ModuleLifespan\>\(ModuleLifespan\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`Singleton = 0` 

Defines that this module will be instantiated once.

`Transient = 1` 

Defines that this module will be instantiated every time a containing command is called.


# Class CommandsNextExtension.DefaultHelpModule

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

```csharp
[ModuleLifespan(ModuleLifespan.Transient)]
public class CommandsNextExtension.DefaultHelpModule : BaseCommandModule
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseCommandModule](DSharpPlus.CommandsNext.BaseCommandModule.md) ← 
[CommandsNextExtension.DefaultHelpModule](DSharpPlus.CommandsNext.CommandsNextExtension.DefaultHelpModule.md)

###### Inherited Members

[BaseCommandModule.BeforeExecutionAsync\(CommandContext\)](DSharpPlus.CommandsNext.BaseCommandModule.md\#DSharpPlus\_CommandsNext\_BaseCommandModule\_BeforeExecutionAsync\_DSharpPlus\_CommandsNext\_CommandContext\_), 
[BaseCommandModule.AfterExecutionAsync\(CommandContext\)](DSharpPlus.CommandsNext.BaseCommandModule.md\#DSharpPlus\_CommandsNext\_BaseCommandModule\_AfterExecutionAsync\_DSharpPlus\_CommandsNext\_CommandContext\_)

## Methods

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_DefaultHelpModule_DefaultHelpAsync_DSharpPlus_CommandsNext_CommandContext_System_String___"></a>DefaultHelpAsync\(CommandContext, params string\[\]\)

```csharp
[Command("help")]
[Description("Displays command help.")]
public Task DefaultHelpAsync(CommandContext ctx, params string[] command)
```

#### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

`command` [string](https://learn.microsoft.com/dotnet/api/system.string)\[\]

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)


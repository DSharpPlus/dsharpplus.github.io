# Class TransientCommandModule

Namespace: [DSharpPlus.CommandsNext.Entities](DSharpPlus.CommandsNext.Entities.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents a transient command module. This type of module is reinstated on every command call.

```csharp
public class TransientCommandModule : ICommandModule
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[TransientCommandModule](DSharpPlus.CommandsNext.Entities.TransientCommandModule.md)

###### Implements

[ICommandModule](DSharpPlus.CommandsNext.Entities.ICommandModule.md)

## Properties

### <a id="DSharpPlus_CommandsNext_Entities_TransientCommandModule_ModuleType"></a>ModuleType

Gets the type of this module.

```csharp
public Type ModuleType { get; }
```

#### Property Value

[Type](https://learn.microsoft.com/dotnet/api/system.type)

## Methods

### <a id="DSharpPlus_CommandsNext_Entities_TransientCommandModule_GetInstance_System_IServiceProvider_"></a>GetInstance\(IServiceProvider\)

Creates a new instance of this module.

```csharp
public BaseCommandModule GetInstance(IServiceProvider services)
```

#### Parameters

`services` [IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider)

Services to instantiate the module with.

#### Returns

[BaseCommandModule](DSharpPlus.CommandsNext.BaseCommandModule.md)

Created module.


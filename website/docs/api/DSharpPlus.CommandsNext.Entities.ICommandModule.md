# Interface ICommandModule

Namespace: [DSharpPlus.CommandsNext.Entities](DSharpPlus.CommandsNext.Entities.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents a base interface for all types of command modules.

```csharp
public interface ICommandModule
```

## Properties

### <a id="DSharpPlus_CommandsNext_Entities_ICommandModule_ModuleType"></a>ModuleType

Gets the type of this module.

```csharp
Type ModuleType { get; }
```

#### Property Value

[Type](https://learn.microsoft.com/dotnet/api/system.type)

## Methods

### <a id="DSharpPlus_CommandsNext_Entities_ICommandModule_GetInstance_System_IServiceProvider_"></a>GetInstance\(IServiceProvider\)

Returns an instance of this module.

```csharp
BaseCommandModule GetInstance(IServiceProvider services)
```

#### Parameters

`services` [IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider)

Services to instantiate the module with.

#### Returns

[BaseCommandModule](DSharpPlus.CommandsNext.BaseCommandModule.md)

A created instance of this module.

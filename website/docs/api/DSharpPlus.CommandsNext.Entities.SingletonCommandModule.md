# Class SingletonCommandModule

Namespace: [DSharpPlus.CommandsNext.Entities](DSharpPlus.CommandsNext.Entities.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents a singleton command module. This type of module is instantiated only when created.

```csharp
public class SingletonCommandModule : ICommandModule
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SingletonCommandModule](DSharpPlus.CommandsNext.Entities.SingletonCommandModule.md)

###### Implements

[ICommandModule](DSharpPlus.CommandsNext.Entities.ICommandModule.md)

## Properties

### <a id="DSharpPlus_CommandsNext_Entities_SingletonCommandModule_Instance"></a>Instance

Gets this module's instance.

```csharp
public BaseCommandModule Instance { get; }
```

#### Property Value

[BaseCommandModule](DSharpPlus.CommandsNext.BaseCommandModule.md)

### <a id="DSharpPlus_CommandsNext_Entities_SingletonCommandModule_ModuleType"></a>ModuleType

Gets the type of this module.

```csharp
public Type ModuleType { get; }
```

#### Property Value

[Type](https://learn.microsoft.com/dotnet/api/system.type)

## Methods

### <a id="DSharpPlus_CommandsNext_Entities_SingletonCommandModule_GetInstance_System_IServiceProvider_"></a>GetInstance\(IServiceProvider\)

Returns the instance of this module.

```csharp
public BaseCommandModule GetInstance(IServiceProvider services)
```

#### Parameters

`services` [IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider)

Services to instantiate the module with.

#### Returns

[BaseCommandModule](DSharpPlus.CommandsNext.BaseCommandModule.md)

This module's instance.


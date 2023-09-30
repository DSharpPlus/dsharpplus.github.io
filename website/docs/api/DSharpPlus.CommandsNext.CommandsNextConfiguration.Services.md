# Property Services

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_Services"></a>Services

<p>Sets the service provider for this CommandsNext instance.</p>
<p>Objects in this provider are used when instantiating command modules. This allows passing data around without resorting to static members.</p>
<p>Defaults to null.</p>

```csharp
public IServiceProvider Services { set; }
```

### Property Value

[IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider)


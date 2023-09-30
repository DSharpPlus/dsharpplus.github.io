# Property Services

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_SlashCommandsConfiguration_Services"></a>Services

<p>Sets the service provider.</p>
<p>Objects in this provider are used when instantiating slash command modules. This allows passing data around without resorting to static members.</p>
<p>Defaults to null.</p>

```csharp
public IServiceProvider Services { set; }
```

### Property Value

[IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider)


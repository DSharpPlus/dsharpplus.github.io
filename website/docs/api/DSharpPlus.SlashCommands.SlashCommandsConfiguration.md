# Class SlashCommandsConfiguration

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

A configuration for a <xref href="DSharpPlus.SlashCommands.SlashCommandsExtension" data-throw-if-not-resolved="false"></xref>.

```csharp
public sealed class SlashCommandsConfiguration
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SlashCommandsConfiguration](DSharpPlus.SlashCommands.SlashCommandsConfiguration.md)

## Properties

### <a id="DSharpPlus_SlashCommands_SlashCommandsConfiguration_Services"></a>Services

<p>Sets the service provider.</p>
<p>Objects in this provider are used when instantiating slash command modules. This allows passing data around without resorting to static members.</p>
<p>Defaults to null.</p>

```csharp
public IServiceProvider Services { set; }
```

#### Property Value

[IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider)


# Class CommandsNextConfiguration

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents a configuration for <xref href="DSharpPlus.CommandsNext.CommandsNextExtension" data-throw-if-not-resolved="false"></xref>.

```csharp
public sealed class CommandsNextConfiguration
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[CommandsNextConfiguration](DSharpPlus.CommandsNext.CommandsNextConfiguration.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration__ctor"></a>CommandsNextConfiguration\(\)

Creates a new instance of <xref href="DSharpPlus.CommandsNext.CommandsNextConfiguration" data-throw-if-not-resolved="false"></xref>.

```csharp
public CommandsNextConfiguration()
```

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration__ctor_DSharpPlus_CommandsNext_CommandsNextConfiguration_"></a>CommandsNextConfiguration\(CommandsNextConfiguration\)

Creates a new instance of <xref href="DSharpPlus.CommandsNext.CommandsNextConfiguration" data-throw-if-not-resolved="false"></xref>, copying the properties of another configuration.

```csharp
public CommandsNextConfiguration(CommandsNextConfiguration other)
```

#### Parameters

`other` [CommandsNextConfiguration](DSharpPlus.CommandsNext.CommandsNextConfiguration.md)

Configuration the properties of which are to be copied.

## Properties

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_CaseSensitive"></a>CaseSensitive

<p>Sets whether strings should be matched in a case-sensitive manner.</p>
<p>This switch affects the behaviour of default prefix resolver, command searching, and argument conversion.</p>
<p>Defaults to false.</p>

```csharp
public bool CaseSensitive { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_CommandExecutor"></a>CommandExecutor

<p>Gets or sets the default command executor.</p>
<p>This alters the behaviour, execution, and scheduling method of command execution.</p>

```csharp
public ICommandExecutor CommandExecutor { set; }
```

#### Property Value

[ICommandExecutor](DSharpPlus.CommandsNext.Executors.ICommandExecutor.md)

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_DefaultHelpChecks"></a>DefaultHelpChecks

<p>Sets the default pre-execution checks for the built-in help command.</p>
<p>Only applicable if default help is enabled.</p>
<p>Defaults to null.</p>

```csharp
public IEnumerable<CheckBaseAttribute> DefaultHelpChecks { set; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md)\>

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_DefaultParserCulture"></a>DefaultParserCulture

<p>Gets or sets the default culture for parsers.</p>
<p>Defaults to invariant.</p>

```csharp
public CultureInfo DefaultParserCulture { set; }
```

#### Property Value

[CultureInfo](https://learn.microsoft.com/dotnet/api/system.globalization.cultureinfo)

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_DmHelp"></a>DmHelp

<p>Controls whether the default help will be sent via DMs or not.</p>
<p>Enabling this will make the bot respond with help via direct messages.</p>
<p>Defaults to false.</p>

```csharp
public bool DmHelp { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_EnableDefaultHelp"></a>EnableDefaultHelp

<p>Sets whether to enable default help command.</p>
<p>Disabling this will allow you to make your own help command.</p>
<p>
Modifying default help can be achieved via custom help formatters (see <xref href="DSharpPlus.CommandsNext.Converters.BaseHelpFormatter" data-throw-if-not-resolved="false"></xref> and <xref href="DSharpPlus.CommandsNext.CommandsNextExtension.SetHelpFormatter%60%601" data-throw-if-not-resolved="false"></xref> for more details).
It is recommended to use help formatter instead of disabling help.
</p>
<p>Defaults to true.</p>

```csharp
public bool EnableDefaultHelp { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_EnableDms"></a>EnableDms

<p>Sets whether commands sent via direct messages should be processed.</p>
<p>Defaults to true.</p>

```csharp
public bool EnableDms { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_EnableMentionPrefix"></a>EnableMentionPrefix

<p>Sets whether to allow mentioning the bot to be used as command prefix.</p>
<p>Defaults to true.</p>

```csharp
public bool EnableMentionPrefix { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_IgnoreExtraArguments"></a>IgnoreExtraArguments

<p>Gets whether any extra arguments passed to commands should be ignored or not. If this is set to false, extra arguments will throw, otherwise they will be ignored.</p>
<p>Defaults to false.</p>

```csharp
public bool IgnoreExtraArguments { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_PrefixResolver"></a>PrefixResolver

<p>Sets the custom prefix resolver used for commands.</p>
<p>Defaults to none (disabled).</p>

```csharp
public PrefixResolverDelegate? PrefixResolver { set; }
```

#### Property Value

[PrefixResolverDelegate](DSharpPlus.CommandsNext.PrefixResolverDelegate.md)?

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_QuotationMarks"></a>QuotationMarks

<p>Sets the quotation marks on parameters, used to interpret spaces as part of a single argument.</p>
<p>Defaults to a collection of <code>"</code>, <code>«</code>, <code>»</code>, <code>‘</code>, <code>“</code>, <code>„</code> and <code>‟</code>.</p>

```csharp
public IEnumerable<char> QuotationMarks { set; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[char](https://learn.microsoft.com/dotnet/api/system.char)\>

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_Services"></a>Services

<p>Sets the service provider for this CommandsNext instance.</p>
<p>Objects in this provider are used when instantiating command modules. This allows passing data around without resorting to static members.</p>
<p>Defaults to null.</p>

```csharp
public IServiceProvider Services { set; }
```

#### Property Value

[IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider)

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_StringPrefixes"></a>StringPrefixes

<p>Sets the string prefixes used for commands.</p>
<p>Defaults to no value (disabled).</p>

```csharp
public IEnumerable<string> StringPrefixes { set; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_UseDefaultCommandHandler"></a>UseDefaultCommandHandler

<p>Gets or sets whether to automatically enable handling commands.</p>
<p>If this is set to false, you will need to manually handle each incoming message and pass it to CommandsNext.</p>
<p>Defaults to true.</p>

```csharp
public bool UseDefaultCommandHandler { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)


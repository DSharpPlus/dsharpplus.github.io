# Property EnableDefaultHelp

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_CommandsNextConfiguration_EnableDefaultHelp"></a>EnableDefaultHelp

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

### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)


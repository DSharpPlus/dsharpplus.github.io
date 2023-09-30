# Constructor ChecksFailedException

Namespace: [DSharpPlus.CommandsNext.Exceptions](DSharpPlus.CommandsNext.Exceptions.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_Exceptions_ChecksFailedException__ctor_DSharpPlus_CommandsNext_Command_DSharpPlus_CommandsNext_CommandContext_System_Collections_Generic_IEnumerable_DSharpPlus_CommandsNext_Attributes_CheckBaseAttribute__"></a>ChecksFailedException\(Command, CommandContext, IEnumerable<CheckBaseAttribute\>\)

Creates a new <xref href="DSharpPlus.CommandsNext.Exceptions.ChecksFailedException" data-throw-if-not-resolved="false"></xref>.

```csharp
public ChecksFailedException(Command command, CommandContext ctx, IEnumerable<CheckBaseAttribute> failedChecks)
```

### Parameters

`command` [Command](DSharpPlus.CommandsNext.Command.md)

Command that failed to execute.

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which the command was executed.

`failedChecks` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md)\>

A collection of checks that failed.


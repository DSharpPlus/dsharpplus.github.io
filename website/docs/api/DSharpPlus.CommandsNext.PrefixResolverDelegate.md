# Delegate PrefixResolverDelegate

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

<p>Represents a delegate for a function that takes a message, and returns the position of the start of command invocation in the message. It has to return -1 if prefix is not present.</p>
<p>
It is recommended that helper methods <xref href="DSharpPlus.CommandsNext.CommandsNextUtilities.GetStringPrefixLength(DSharpPlus.Entities.DiscordMessage%2cSystem.String%2cSystem.StringComparison)" data-throw-if-not-resolved="false"></xref> and <xref href="DSharpPlus.CommandsNext.CommandsNextUtilities.GetMentionPrefixLength(DSharpPlus.Entities.DiscordMessage%2cDSharpPlus.Entities.DiscordUser)" data-throw-if-not-resolved="false"></xref>
be used internally for checking. Their output can be passed through.
</p>

```csharp
public delegate Task<int> PrefixResolverDelegate(DiscordMessage msg)
```

#### Parameters

`msg` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message to check for prefix.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

Position of the command invocation or -1 if not present.


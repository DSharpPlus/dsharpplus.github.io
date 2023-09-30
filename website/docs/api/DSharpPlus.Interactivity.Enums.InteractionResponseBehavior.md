# Enum InteractionResponseBehavior

Namespace: [DSharpPlus.Interactivity.Enums](DSharpPlus.Interactivity.Enums.md)  
Assembly: DSharpPlus.Interactivity.dll

```csharp
public enum InteractionResponseBehavior
```

###### Extension Methods

[ExtensionMethods.GetName<InteractionResponseBehavior\>\(InteractionResponseBehavior\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`Ack = 1` 

Indicates that invalid input should be ACK'd. The interaction will succeed, but nothing will happen.

`Ignore = 0` 

Indicates that invalid input should be ignored when waiting for interactions. This will cause the interaction to fail.

`Respond = 2` 

Indicates that invalid input should warrant an ephemeral error message.


# Enum InteractionResponseType

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Represents the type of interaction response

```csharp
public enum InteractionResponseType
```

###### Extension Methods

[ExtensionMethods.GetName<InteractionResponseType\>\(InteractionResponseType\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`AutoCompleteResult = 8` 

Responds to an auto-complete request.

`ChannelMessageWithSource = 4` 

Responds to the interaction with a message.

`DeferredChannelMessageWithSource = 5` 

Acknowledges an interaction to edit to a response later. The user sees a "thinking" state.

`DeferredMessageUpdate = 6` 

Acknowledges a component interaction to allow a response later.

`Modal = 9` 

Respond to an interaction with a modal popup.

`Pong = 1` 

Acknowledges a Ping.

`UpdateMessage = 7` 

Responds to a component interaction by editing the message it's attached to.


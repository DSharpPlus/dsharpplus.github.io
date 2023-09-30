# Class InteractivityConfiguration

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

Configuration class for your Interactivity extension

```csharp
public sealed class InteractivityConfiguration
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[InteractivityConfiguration](DSharpPlus.Interactivity.InteractivityConfiguration.md)

## Constructors

### <a id="DSharpPlus_Interactivity_InteractivityConfiguration__ctor"></a>InteractivityConfiguration\(\)

Creates a new instance of <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

```csharp
public InteractivityConfiguration()
```

### <a id="DSharpPlus_Interactivity_InteractivityConfiguration__ctor_DSharpPlus_Interactivity_InteractivityConfiguration_"></a>InteractivityConfiguration\(InteractivityConfiguration\)

Creates a new instance of <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>, copying the properties of another configuration.

```csharp
public InteractivityConfiguration(InteractivityConfiguration other)
```

#### Parameters

`other` [InteractivityConfiguration](DSharpPlus.Interactivity.InteractivityConfiguration.md)

Configuration the properties of which are to be copied.

## Properties

### <a id="DSharpPlus_Interactivity_InteractivityConfiguration_ButtonBehavior"></a>ButtonBehavior

How to handle buttons after pagination ends.

```csharp
public ButtonPaginationBehavior ButtonBehavior { set; }
```

#### Property Value

[ButtonPaginationBehavior](DSharpPlus.Interactivity.Enums.ButtonPaginationBehavior.md)

### <a id="DSharpPlus_Interactivity_InteractivityConfiguration_PaginationBehaviour"></a>PaginationBehaviour

How to handle pagination. Defaults to WrapAround.

```csharp
public PaginationBehaviour PaginationBehaviour { set; }
```

#### Property Value

[PaginationBehaviour](DSharpPlus.Interactivity.Enums.PaginationBehaviour.md)

### <a id="DSharpPlus_Interactivity_InteractivityConfiguration_PaginationButtons"></a>PaginationButtons

Buttons to use for pagination.

```csharp
public PaginationButtons PaginationButtons { set; }
```

#### Property Value

[PaginationButtons](DSharpPlus.Interactivity.EventHandling.PaginationButtons.md)

### <a id="DSharpPlus_Interactivity_InteractivityConfiguration_PaginationDeletion"></a>PaginationDeletion

How to handle pagination deletion. Defaults to DeleteEmojis.

```csharp
public PaginationDeletion PaginationDeletion { set; }
```

#### Property Value

[PaginationDeletion](DSharpPlus.Interactivity.Enums.PaginationDeletion.md)

### <a id="DSharpPlus_Interactivity_InteractivityConfiguration_PaginationEmojis"></a>PaginationEmojis

Emojis to use for pagination

```csharp
public PaginationEmojis PaginationEmojis { set; }
```

#### Property Value

[PaginationEmojis](DSharpPlus.Interactivity.PaginationEmojis.md)

### <a id="DSharpPlus_Interactivity_InteractivityConfiguration_PollBehaviour"></a>PollBehaviour

What to do after the poll ends

```csharp
public PollBehaviour PollBehaviour { set; }
```

#### Property Value

[PollBehaviour](DSharpPlus.Interactivity.Enums.PollBehaviour.md)

### <a id="DSharpPlus_Interactivity_InteractivityConfiguration_ResponseBehavior"></a>ResponseBehavior

How to handle invalid interactions. Defaults to Ignore.

```csharp
public InteractionResponseBehavior ResponseBehavior { set; }
```

#### Property Value

[InteractionResponseBehavior](DSharpPlus.Interactivity.Enums.InteractionResponseBehavior.md)

### <a id="DSharpPlus_Interactivity_InteractivityConfiguration_ResponseMessage"></a>ResponseMessage

The message to send to the user when processing invalid interactions. Ignored if <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.ResponseBehavior" data-throw-if-not-resolved="false"></xref> is not set to <xref href="DSharpPlus.Interactivity.Enums.InteractionResponseBehavior.Respond" data-throw-if-not-resolved="false"></xref>.

```csharp
public string ResponseMessage { set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Interactivity_InteractivityConfiguration_Timeout"></a>Timeout

<p>Sets the default interactivity action timeout.</p>
<p>Defaults to 1 minute.</p>

```csharp
public TimeSpan Timeout { set; }
```

#### Property Value

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)


# Constructor DiscordChannelSelectComponent

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannelSelectComponent__ctor_System_String_System_String_System_Collections_Generic_IEnumerable_DSharpPlus_ChannelType__System_Boolean_System_Int32_System_Int32_"></a>DiscordChannelSelectComponent\(string, string, IEnumerable<ChannelType\>?, bool, int, int\)

Creates a new channel select component.

```csharp
public DiscordChannelSelectComponent(string customId, string placeholder, IEnumerable<ChannelType>? channelTypes = null, bool disabled = false, int minOptions = 1, int maxOptions = 1)
```

### Parameters

`customId` [string](https://learn.microsoft.com/dotnet/api/system.string)

The ID of this component.

`placeholder` [string](https://learn.microsoft.com/dotnet/api/system.string)

Placeholder text that's shown when no options are selected.

`channelTypes` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ChannelType](DSharpPlus.ChannelType.md)\>?

Optional channel types to filter by.

`disabled` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this component is disabled.

`minOptions` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The minimum amount of options to be selected.

`maxOptions` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The maximum amount of options to be selected, up to 25.


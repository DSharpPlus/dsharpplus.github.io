# Class DiscordIntentExtensions

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

```csharp
public static class DiscordIntentExtensions
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordIntentExtensions](DSharpPlus.DiscordIntentExtensions.md)

## Methods

### <a id="DSharpPlus_DiscordIntentExtensions_AddIntent_DSharpPlus_DiscordIntents_DSharpPlus_DiscordIntents_"></a>AddIntent\(DiscordIntents, DiscordIntents\)

Adds an intent to these intents.

```csharp
public static DiscordIntents AddIntent(this DiscordIntents intents, DiscordIntents toAdd)
```

#### Parameters

`intents` [DiscordIntents](DSharpPlus.DiscordIntents.md)

The base intents.

`toAdd` [DiscordIntents](DSharpPlus.DiscordIntents.md)

The intents to add.

#### Returns

[DiscordIntents](DSharpPlus.DiscordIntents.md)

### <a id="DSharpPlus_DiscordIntentExtensions_HasIntent_DSharpPlus_DiscordIntents_DSharpPlus_DiscordIntents_"></a>HasIntent\(DiscordIntents, DiscordIntents\)

Calculates whether these intents have a certain intent.

```csharp
public static bool HasIntent(this DiscordIntents intents, DiscordIntents search)
```

#### Parameters

`intents` [DiscordIntents](DSharpPlus.DiscordIntents.md)

The base intents.

`search` [DiscordIntents](DSharpPlus.DiscordIntents.md)

The intents to search for.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_DiscordIntentExtensions_RemoveIntent_DSharpPlus_DiscordIntents_DSharpPlus_DiscordIntents_"></a>RemoveIntent\(DiscordIntents, DiscordIntents\)

Removes an intent from these intents.

```csharp
public static DiscordIntents RemoveIntent(this DiscordIntents intents, DiscordIntents toRemove)
```

#### Parameters

`intents` [DiscordIntents](DSharpPlus.DiscordIntents.md)

The base intents.

`toRemove` [DiscordIntents](DSharpPlus.DiscordIntents.md)

The intents to remove.

#### Returns

[DiscordIntents](DSharpPlus.DiscordIntents.md)


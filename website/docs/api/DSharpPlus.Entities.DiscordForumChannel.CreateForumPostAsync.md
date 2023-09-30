# Method CreateForumPostAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordForumChannel_CreateForumPostAsync_DSharpPlus_Entities_ForumPostBuilder_"></a>CreateForumPostAsync\(ForumPostBuilder\)

Creates a forum post.

```csharp
public Task<DiscordForumPostStarter> CreateForumPostAsync(ForumPostBuilder builder)
```

### Parameters

`builder` [ForumPostBuilder](DSharpPlus.Entities.ForumPostBuilder.md)

The builder to create the forum post with.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordForumPostStarter](DSharpPlus.Entities.DiscordForumPostStarter.md)\>

The starter (the created thread, and the initial message) from creating the post.


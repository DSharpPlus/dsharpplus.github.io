# Enum OAuthScope

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents the possible OAuth scopes for application authorization.

```csharp
public enum OAuthScope
```

###### Extension Methods

[ExtensionMethods.GetName<OAuthScope\>\(OAuthScope\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`ActivitiesRead = 20` 

Allows your application to fetch data from a user's "Now Playing/Recently Played" list.

`ActivitiesWrite = 21` 

Allows your application to update a user's activity.

`ApplicationsBuildsRead = 16` 

Allows your application to read build data for a user's applications.

`ApplicationsBuildsUpload = 15` 

Allows your application to upload/update builds for a user's applications.

`ApplicationsCommands = 17` 

Allows your application to use application commands in a guild.

`ApplicationsEntitlements = 19` 

Allows your application to read entitlements for a user's applications.

`ApplicationsStoreUpdate = 18` 

Allows your application to read and update store data (SKUs, store listings, achievements etc.) for a user's applications.

`Bot = 12` 

For OAuth2 bots, this puts the bot in the user's selected guild by default.

`Connections = 2` 

Allows <code>/users/@me/connections</code> to return linked third-party accounts.

`Email = 1` 

Enables <code>/users/@me</code> to return <code>email</code>.

`GdmJoin = 6` 

Allows your app to join users into a group DM.

`Guilds = 3` 

Allows <code>/users/@me/guilds</code> to return basic information about all of a user's guilds.

`GuildsJoin = 4` 

Allows <code>/guilds/{guild.id}/members/{user.id}</code> to be used for joining users into a guild.

`GuildsMembersRead = 5` 

Allows <code>/users/@me/guilds/{guild.id}/members</code> to return a user's member information in a guild.

`Identify = 0` 

Allows <code>/users/@me</code> without <code>email</code>.

`MessagesRead = 14` 

For local RPC server access, this allows you to read messages from all client channels
(otherwise restricted to channels/guilds your application creates).

`RelationshipsRead = 22` 

Allows your application to know a user's friends and implicit relationships.

`Rpc = 7` 

For local RPC server access, this allows you to control a user's local Discord client.

`RpcActivitiesWrite = 11` 

For local RPC server access, this allows you to update a user's activity.

`RpcNotificationsRead = 8` 

For local RPC server access, this allows you to receive notifications pushed to the user.

`RpcVoiceRead = 9` 

For local RPC server access, this allows you to read a user's voice settings and listen for voice events.

`RpcVoiceWrite = 10` 

For local RPC server access, this allows you to update a user's voice settings.

`WebhookIncoming = 13` 

This generates a webhook that is returned in the OAuth token response for authorization code grants.


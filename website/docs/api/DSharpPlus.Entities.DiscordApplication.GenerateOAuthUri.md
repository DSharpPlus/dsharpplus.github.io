# Method GenerateOAuthUri

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordApplication_GenerateOAuthUri_System_String_System_Nullable_DSharpPlus_Permissions__DSharpPlus_Entities_OAuthScope___"></a>GenerateOAuthUri\(string, Permissions?, params OAuthScope\[\]\)

Generates a new OAuth2 URI for this application.

```csharp
public string GenerateOAuthUri(string redirectUri = null, Permissions? permissions = null, params OAuthScope[] scopes)
```

### Parameters

`redirectUri` [string](https://learn.microsoft.com/dotnet/api/system.string)

Redirect URI - the URI Discord will redirect users to as part of the OAuth flow.
    <remarks>
    This URI <b>must</b> be already registered as a valid redirect URI for your application on the developer portal.
    </remarks>

`permissions` [Permissions](DSharpPlus.Permissions.md)?

Permissions for your bot. Only required if the <xref href="DSharpPlus.Entities.OAuthScope.Bot" data-throw-if-not-resolved="false"></xref> scope is passed.

`scopes` [OAuthScope](DSharpPlus.Entities.OAuthScope.md)\[\]

OAuth scopes for your application.

### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)


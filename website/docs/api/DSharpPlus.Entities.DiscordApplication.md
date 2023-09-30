# Class DiscordApplication

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents an OAuth2 application.

```csharp
public sealed class DiscordApplication : DiscordMessageApplication
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordMessageApplication](DSharpPlus.Entities.DiscordMessageApplication.md) ← 
[DiscordApplication](DSharpPlus.Entities.DiscordApplication.md)

###### Inherited Members

[DiscordMessageApplication.CoverImageUrl](DSharpPlus.Entities.DiscordMessageApplication.md\#DSharpPlus\_Entities\_DiscordMessageApplication\_CoverImageUrl), 
[DiscordMessageApplication.Description](DSharpPlus.Entities.DiscordMessageApplication.md\#DSharpPlus\_Entities\_DiscordMessageApplication\_Description), 
[DiscordMessageApplication.Icon](DSharpPlus.Entities.DiscordMessageApplication.md\#DSharpPlus\_Entities\_DiscordMessageApplication\_Icon), 
[DiscordMessageApplication.Name](DSharpPlus.Entities.DiscordMessageApplication.md\#DSharpPlus\_Entities\_DiscordMessageApplication\_Name), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordApplication_CoverImageHash"></a>CoverImageHash

Gets the hash of the application's cover image.

```csharp
public string CoverImageHash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplication_CoverImageUrl"></a>CoverImageUrl

Gets this application's cover image URL.

```csharp
public override string CoverImageUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplication_Flags"></a>Flags

Gets the application's flags.

```csharp
public ApplicationFlags? Flags { get; }
```

#### Property Value

[ApplicationFlags](DSharpPlus.ApplicationFlags.md)?

### <a id="DSharpPlus_Entities_DiscordApplication_Icon"></a>Icon

Gets the application's icon.

```csharp
public override string Icon { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplication_IconHash"></a>IconHash

Gets the application's icon hash.

```csharp
public string IconHash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplication_IsPublic"></a>IsPublic

Gets whether this bot application is public.

```csharp
public bool? IsPublic { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordApplication_Owners"></a>Owners

Gets the application's owners.

```csharp
public IEnumerable<DiscordUser> Owners { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

### <a id="DSharpPlus_Entities_DiscordApplication_PrivacyPolicyUrl"></a>PrivacyPolicyUrl

Gets the application's privacy policy URL.

```csharp
public string PrivacyPolicyUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplication_RequiresCodeGrant"></a>RequiresCodeGrant

Gets whether this application's bot user requires code grant.

```csharp
public bool? RequiresCodeGrant { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordApplication_RpcOrigins"></a>RpcOrigins

Gets the application's allowed RPC origins.

```csharp
public IReadOnlyList<string> RpcOrigins { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_DiscordApplication_Summary"></a>Summary

Gets the application's summary.

```csharp
public string Summary { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplication_Team"></a>Team

Gets the team which owns this application.

```csharp
public DiscordTeam Team { get; }
```

#### Property Value

[DiscordTeam](DSharpPlus.Entities.DiscordTeam.md)

### <a id="DSharpPlus_Entities_DiscordApplication_TermsOfServiceUrl"></a>TermsOfServiceUrl

Gets the application's terms of service URL.

```csharp
public string TermsOfServiceUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="DSharpPlus_Entities_DiscordApplication_Equals_System_Object_"></a>Equals\(object\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordApplication" data-throw-if-not-resolved="false"></xref> is equal to another object.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the object is equal to this <xref href="DSharpPlus.Entities.DiscordApplication" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordApplication_Equals_DSharpPlus_Entities_DiscordApplication_"></a>Equals\(DiscordApplication\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordApplication" data-throw-if-not-resolved="false"></xref> is equal to another <xref href="DSharpPlus.Entities.DiscordApplication" data-throw-if-not-resolved="false"></xref>.

```csharp
public bool Equals(DiscordApplication e)
```

#### Parameters

`e` [DiscordApplication](DSharpPlus.Entities.DiscordApplication.md)

<xref href="DSharpPlus.Entities.DiscordApplication" data-throw-if-not-resolved="false"></xref> to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the <xref href="DSharpPlus.Entities.DiscordApplication" data-throw-if-not-resolved="false"></xref> is equal to this <xref href="DSharpPlus.Entities.DiscordApplication" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordApplication_GenerateBotOAuth_DSharpPlus_Permissions_"></a>GenerateBotOAuth\(Permissions\)

```csharp
public string GenerateBotOAuth(Permissions permissions = Permissions.None)
```

#### Parameters

`permissions` [Permissions](DSharpPlus.Permissions.md)

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplication_GenerateOAuthUri_System_String_System_Nullable_DSharpPlus_Permissions__DSharpPlus_Entities_OAuthScope___"></a>GenerateOAuthUri\(string, Permissions?, params OAuthScope\[\]\)

Generates a new OAuth2 URI for this application.

```csharp
public string GenerateOAuthUri(string redirectUri = null, Permissions? permissions = null, params OAuthScope[] scopes)
```

#### Parameters

`redirectUri` [string](https://learn.microsoft.com/dotnet/api/system.string)

Redirect URI - the URI Discord will redirect users to as part of the OAuth flow.
    <remarks>
    This URI <b>must</b> be already registered as a valid redirect URI for your application on the developer portal.
    </remarks>

`permissions` [Permissions](DSharpPlus.Permissions.md)?

Permissions for your bot. Only required if the <xref href="DSharpPlus.Entities.OAuthScope.Bot" data-throw-if-not-resolved="false"></xref> scope is passed.

`scopes` [OAuthScope](DSharpPlus.Entities.OAuthScope.md)\[\]

OAuth scopes for your application.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplication_GetAssetsAsync_System_Boolean_"></a>GetAssetsAsync\(bool\)

Retrieves this application's assets.

```csharp
public Task<IReadOnlyList<DiscordApplicationAsset>> GetAssetsAsync(bool updateCache = false)
```

#### Parameters

`updateCache` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to always make a REST request and update the cached assets.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationAsset](DSharpPlus.Entities.DiscordApplicationAsset.md)\>\>

This application's assets.

### <a id="DSharpPlus_Entities_DiscordApplication_GetAvatarUrl_DSharpPlus_ImageFormat_System_UInt16_"></a>GetAvatarUrl\(ImageFormat, ushort\)

Gets the application's cover image URL, in requested format and size.

```csharp
public string GetAvatarUrl(ImageFormat fmt, ushort size = 1024)
```

#### Parameters

`fmt` [ImageFormat](DSharpPlus.ImageFormat.md)

Format of the image to get.

`size` [ushort](https://learn.microsoft.com/dotnet/api/system.uint16)

Maximum size of the cover image. Must be a power of two, minimum 16, maximum 2048.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

URL of the application's cover image.

### <a id="DSharpPlus_Entities_DiscordApplication_GetHashCode"></a>GetHashCode\(\)

Gets the hash code for this <xref href="DSharpPlus.Entities.DiscordApplication" data-throw-if-not-resolved="false"></xref>.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The hash code for this <xref href="DSharpPlus.Entities.DiscordApplication" data-throw-if-not-resolved="false"></xref>.

## Operators

### <a id="DSharpPlus_Entities_DiscordApplication_op_Equality_DSharpPlus_Entities_DiscordApplication_DSharpPlus_Entities_DiscordApplication_"></a>operator ==\(DiscordApplication, DiscordApplication\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordApplication" data-throw-if-not-resolved="false"></xref> objects are equal.

```csharp
public static bool operator ==(DiscordApplication e1, DiscordApplication e2)
```

#### Parameters

`e1` [DiscordApplication](DSharpPlus.Entities.DiscordApplication.md)

First application to compare.

`e2` [DiscordApplication](DSharpPlus.Entities.DiscordApplication.md)

Second application to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two applications are equal.

### <a id="DSharpPlus_Entities_DiscordApplication_op_Inequality_DSharpPlus_Entities_DiscordApplication_DSharpPlus_Entities_DiscordApplication_"></a>operator \!=\(DiscordApplication, DiscordApplication\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordApplication" data-throw-if-not-resolved="false"></xref> objects are not equal.

```csharp
public static bool operator !=(DiscordApplication e1, DiscordApplication e2)
```

#### Parameters

`e1` [DiscordApplication](DSharpPlus.Entities.DiscordApplication.md)

First application to compare.

`e2` [DiscordApplication](DSharpPlus.Entities.DiscordApplication.md)

Second application to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two applications are not equal.


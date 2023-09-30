# Class DiscordTeamMember

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a member of <xref href="DSharpPlus.Entities.DiscordTeam" data-throw-if-not-resolved="false"></xref>.

```csharp
public sealed class DiscordTeamMember
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordTeamMember](DSharpPlus.Entities.DiscordTeamMember.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordTeamMember_MembershipStatus"></a>MembershipStatus

Gets the member's membership status.

```csharp
public DiscordTeamMembershipStatus MembershipStatus { get; }
```

#### Property Value

[DiscordTeamMembershipStatus](DSharpPlus.Entities.DiscordTeamMembershipStatus.md)

### <a id="DSharpPlus_Entities_DiscordTeamMember_Permissions"></a>Permissions

Gets the member's permissions within the team.

```csharp
public IReadOnlyCollection<string> Permissions { get; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_DiscordTeamMember_Team"></a>Team

Gets the team this member belongs to.

```csharp
public DiscordTeam Team { get; }
```

#### Property Value

[DiscordTeam](DSharpPlus.Entities.DiscordTeam.md)

### <a id="DSharpPlus_Entities_DiscordTeamMember_User"></a>User

Gets the user who is the team member.

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordTeamMember_Equals_System_Object_"></a>Equals\(object\)

Compares this team member to another object and returns whether they are equal.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this team is equal to given object.

### <a id="DSharpPlus_Entities_DiscordTeamMember_Equals_DSharpPlus_Entities_DiscordTeamMember_"></a>Equals\(DiscordTeamMember\)

Compares this team member to another team member and returns whether they are equal.

```csharp
public bool Equals(DiscordTeamMember other)
```

#### Parameters

`other` [DiscordTeamMember](DSharpPlus.Entities.DiscordTeamMember.md)

Team member to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this team member is equal to the given one.

### <a id="DSharpPlus_Entities_DiscordTeamMember_GetHashCode"></a>GetHashCode\(\)

Gets a hash code of this team member.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

Hash code of this team member.

### <a id="DSharpPlus_Entities_DiscordTeamMember_ToString"></a>ToString\(\)

Converts this team member to their string representation.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

String representation of this team member.

## Operators

### <a id="DSharpPlus_Entities_DiscordTeamMember_op_Equality_DSharpPlus_Entities_DiscordTeamMember_DSharpPlus_Entities_DiscordTeamMember_"></a>operator ==\(DiscordTeamMember, DiscordTeamMember\)

```csharp
public static bool operator ==(DiscordTeamMember left, DiscordTeamMember right)
```

#### Parameters

`left` [DiscordTeamMember](DSharpPlus.Entities.DiscordTeamMember.md)

`right` [DiscordTeamMember](DSharpPlus.Entities.DiscordTeamMember.md)

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordTeamMember_op_Inequality_DSharpPlus_Entities_DiscordTeamMember_DSharpPlus_Entities_DiscordTeamMember_"></a>operator \!=\(DiscordTeamMember, DiscordTeamMember\)

```csharp
public static bool operator !=(DiscordTeamMember left, DiscordTeamMember right)
```

#### Parameters

`left` [DiscordTeamMember](DSharpPlus.Entities.DiscordTeamMember.md)

`right` [DiscordTeamMember](DSharpPlus.Entities.DiscordTeamMember.md)

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)


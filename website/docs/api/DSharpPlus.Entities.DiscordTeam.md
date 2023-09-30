# Class DiscordTeam

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a team consisting of users. A team can own an application.

```csharp
public sealed class DiscordTeam : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordTeam](DSharpPlus.Entities.DiscordTeam.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordTeam_Icon"></a>Icon

Gets the team's icon.

```csharp
public string Icon { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordTeam_IconHash"></a>IconHash

Gets the team's icon hash.

```csharp
public string IconHash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordTeam_Members"></a>Members

Gets the members of this team.

```csharp
public IReadOnlyList<DiscordTeamMember> Members { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordTeamMember](DSharpPlus.Entities.DiscordTeamMember.md)\>

### <a id="DSharpPlus_Entities_DiscordTeam_Name"></a>Name

Gets the team's name.

```csharp
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordTeam_Owner"></a>Owner

Gets the owner of the team.

```csharp
public DiscordUser Owner { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordTeam_Equals_System_Object_"></a>Equals\(object\)

Compares this team to another object and returns whether they are equal.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare this team to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this team is equal to the given object.

### <a id="DSharpPlus_Entities_DiscordTeam_Equals_DSharpPlus_Entities_DiscordTeam_"></a>Equals\(DiscordTeam\)

Compares this team to another team and returns whether they are equal.

```csharp
public bool Equals(DiscordTeam other)
```

#### Parameters

`other` [DiscordTeam](DSharpPlus.Entities.DiscordTeam.md)

Team to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the teams are equal.

### <a id="DSharpPlus_Entities_DiscordTeam_GetHashCode"></a>GetHashCode\(\)

Gets the hash code of this team.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

Hash code of this team.

### <a id="DSharpPlus_Entities_DiscordTeam_ToString"></a>ToString\(\)

Converts this team to its string representation.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

The string representation of this team.

## Operators

### <a id="DSharpPlus_Entities_DiscordTeam_op_Equality_DSharpPlus_Entities_DiscordTeam_DSharpPlus_Entities_DiscordTeam_"></a>operator ==\(DiscordTeam, DiscordTeam\)

```csharp
public static bool operator ==(DiscordTeam left, DiscordTeam right)
```

#### Parameters

`left` [DiscordTeam](DSharpPlus.Entities.DiscordTeam.md)

`right` [DiscordTeam](DSharpPlus.Entities.DiscordTeam.md)

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordTeam_op_Inequality_DSharpPlus_Entities_DiscordTeam_DSharpPlus_Entities_DiscordTeam_"></a>operator \!=\(DiscordTeam, DiscordTeam\)

```csharp
public static bool operator !=(DiscordTeam left, DiscordTeam right)
```

#### Parameters

`left` [DiscordTeam](DSharpPlus.Entities.DiscordTeam.md)

`right` [DiscordTeam](DSharpPlus.Entities.DiscordTeam.md)

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)


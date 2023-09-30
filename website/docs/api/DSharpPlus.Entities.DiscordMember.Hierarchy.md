# Property Hierarchy

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMember_Hierarchy"></a>Hierarchy

Gets the member's position in the role hierarchy, which is the member's highest role's position. Returns <xref href="System.Int32.MaxValue" data-throw-if-not-resolved="false"></xref> for the guild's owner.

```csharp
[JsonIgnore]
public int Hierarchy { get; }
```

### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)


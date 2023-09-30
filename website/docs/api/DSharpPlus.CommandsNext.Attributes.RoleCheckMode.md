# Enum RoleCheckMode

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Specifies how <xref href="DSharpPlus.CommandsNext.Attributes.RequireRolesAttribute" data-throw-if-not-resolved="false"></xref> checks for roles.

```csharp
[Flags]
public enum RoleCheckMode
```

###### Extension Methods

[ExtensionMethods.GetName<RoleCheckMode\>\(RoleCheckMode\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`All = 1` 

Member is required to have all of the specified roles.

`Any = 2` 

Member is required to have any of the specified roles.

`MatchIds = 16` 

Instructs the check to evaluate for matching role IDs.

`MatchNames = 8` 

Instructs the check to evaluate for matching role names.

`None = 0` 

Member is required to have none of the specified roles.

`SpecifiedOnly = 4` 

Member is required to have exactly the same roles as specified; no extra roles may be present.


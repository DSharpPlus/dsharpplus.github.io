# Class PermissionStringAttribute

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Defines a readable name for this permission.

```csharp
[AttributeUsage(AttributeTargets.Field, AllowMultiple = false)]
public sealed class PermissionStringAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[PermissionStringAttribute](DSharpPlus.PermissionStringAttribute.md)

## Constructors

### <a id="DSharpPlus_PermissionStringAttribute__ctor_System_String_"></a>PermissionStringAttribute\(string\)

Defines a readable name for this permission.

```csharp
public PermissionStringAttribute(string str)
```

#### Parameters

`str` [string](https://learn.microsoft.com/dotnet/api/system.string)

Readable name for this permission.

## Properties

### <a id="DSharpPlus_PermissionStringAttribute_String"></a>String

Gets the readable name for this permission.

```csharp
public string String { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)


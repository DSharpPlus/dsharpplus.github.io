# Struct PropertyChange<T\>

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

Represents a description of how a property changed.

```csharp
public readonly record struct PropertyChange<T>
```

#### Type Parameters

`T` 

Type of the changed property.

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_PropertyChange_1_After"></a>After

The property's value after it was changed.

```csharp
public T After { get; }
```

#### Property Value

T

### <a id="DSharpPlus_Entities_AuditLogs_PropertyChange_1_Before"></a>Before

The property's value before it was changed.

```csharp
public T Before { get; }
```

#### Property Value

T

## Methods

### <a id="DSharpPlus_Entities_AuditLogs_PropertyChange_1_From_System_Object_System_Object_"></a>From\(object, object\)

Create a new <xref href="DSharpPlus.Entities.AuditLogs.PropertyChange%601" data-throw-if-not-resolved="false"></xref> from the given before and after values.

```csharp
public static PropertyChange<T> From(object before, object after)
```

#### Parameters

`before` [object](https://learn.microsoft.com/dotnet/api/system.object)

`after` [object](https://learn.microsoft.com/dotnet/api/system.object)

#### Returns

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<T\>


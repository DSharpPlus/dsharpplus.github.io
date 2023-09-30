# Struct ConnectionEndpoint

Namespace: [DSharpPlus.Net](DSharpPlus.Net.md)  
Assembly: DSharpPlus.dll

Represents a network connection endpoint.

```csharp
public struct ConnectionEndpoint
```

## Constructors

### <a id="DSharpPlus_Net_ConnectionEndpoint__ctor_System_String_System_Int32_System_Boolean_"></a>ConnectionEndpoint\(string, int, bool\)

Creates a new endpoint structure.

```csharp
public ConnectionEndpoint(string hostname, int port, bool secured = false)
```

#### Parameters

`hostname` [string](https://learn.microsoft.com/dotnet/api/system.string)

Hostname to connect to.

`port` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Port to use for connection.

`secured` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the connection should be secured (https/wss).

## Properties

### <a id="DSharpPlus_Net_ConnectionEndpoint_Hostname"></a>Hostname

Gets or sets the hostname associated with this endpoint.

```csharp
public string Hostname { readonly get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Net_ConnectionEndpoint_Port"></a>Port

Gets or sets the port associated with this endpoint.

```csharp
public int Port { readonly get; set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Net_ConnectionEndpoint_Secured"></a>Secured

Gets or sets the secured status of this connection.

```csharp
public bool Secured { readonly get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

## Methods

### <a id="DSharpPlus_Net_ConnectionEndpoint_GetHashCode"></a>GetHashCode\(\)

Gets the hash code of this endpoint.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

Hash code of this endpoint.

### <a id="DSharpPlus_Net_ConnectionEndpoint_ToString"></a>ToString\(\)

Gets the string representation of this connection endpoint.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

String representation of this endpoint.


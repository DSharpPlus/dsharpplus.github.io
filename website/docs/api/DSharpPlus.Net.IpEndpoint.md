# Struct IpEndpoint

Namespace: [DSharpPlus.Net](DSharpPlus.Net.md)  
Assembly: DSharpPlus.dll

Represents a network connection IP endpoint.

```csharp
public struct IpEndpoint
```

## Constructors

### <a id="DSharpPlus_Net_IpEndpoint__ctor_System_Net_IPAddress_System_Int32_"></a>IpEndpoint\(IPAddress, int\)

Creates a new IP endpoint structure.

```csharp
public IpEndpoint(IPAddress address, int port)
```

#### Parameters

`address` [IPAddress](https://learn.microsoft.com/dotnet/api/system.net.ipaddress)

IP address to connect to.

`port` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Port to use for connection.

## Properties

### <a id="DSharpPlus_Net_IpEndpoint_Address"></a>Address

Gets or sets the hostname associated with this endpoint.

```csharp
public IPAddress Address { readonly get; set; }
```

#### Property Value

[IPAddress](https://learn.microsoft.com/dotnet/api/system.net.ipaddress)

### <a id="DSharpPlus_Net_IpEndpoint_Port"></a>Port

Gets or sets the port associated with this endpoint.

```csharp
public int Port { readonly get; set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)


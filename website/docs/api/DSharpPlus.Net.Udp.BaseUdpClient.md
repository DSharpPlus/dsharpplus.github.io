# Class BaseUdpClient

Namespace: [DSharpPlus.Net.Udp](DSharpPlus.Net.Udp.md)  
Assembly: DSharpPlus.dll

Represents a base abstraction for all UDP client implementations.

```csharp
public abstract class BaseUdpClient
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseUdpClient](DSharpPlus.Net.Udp.BaseUdpClient.md)

## Methods

### <a id="DSharpPlus_Net_Udp_BaseUdpClient_Close"></a>Close\(\)

Closes and disposes the client.

```csharp
public abstract void Close()
```

### <a id="DSharpPlus_Net_Udp_BaseUdpClient_ReceiveAsync"></a>ReceiveAsync\(\)

Receives a datagram.

```csharp
public abstract Task<byte[]> ReceiveAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]\>

The received bytes.

### <a id="DSharpPlus_Net_Udp_BaseUdpClient_SendAsync_System_Byte___System_Int32_"></a>SendAsync\(byte\[\], int\)

Sends a datagram.

```csharp
public abstract Task SendAsync(byte[] data, int dataLength)
```

#### Parameters

`data` [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

Datagram.

`dataLength` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Length of the datagram.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Net_Udp_BaseUdpClient_Setup_DSharpPlus_Net_ConnectionEndpoint_"></a>Setup\(ConnectionEndpoint\)

Configures the UDP client.

```csharp
public abstract void Setup(ConnectionEndpoint endpoint)
```

#### Parameters

`endpoint` [ConnectionEndpoint](DSharpPlus.Net.ConnectionEndpoint.md)

Endpoint that the client will be communicating with.


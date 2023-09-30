# Method SendPayloadAsync<T\>

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_SendPayloadAsync__1_DSharpPlus_Net_Abstractions_GatewayOpCode___0_"></a>SendPayloadAsync<T\>\(GatewayOpCode, T\)

Sends a raw payload to the gateway. This method is not recommended for use unless you know what you're doing.

```csharp
[Obsolete("This method should not be used unless you know what you're doing. Instead, look towards the other explicitly implemented methods which come with client-side validation.")]
public Task SendPayloadAsync<T>(GatewayOpCode opCode, T data)
```

### Parameters

`opCode` [GatewayOpCode](DSharpPlus.Net.Abstractions.GatewayOpCode.md)

The opcode to send to the Discord gateway.

`data` T

The data to deserialize.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

A task representing the payload being sent.

### Type Parameters

`T` 

The type of data that the object belongs to.

## <a id="DSharpPlus_DiscordClient_SendPayloadAsync_DSharpPlus_Net_Abstractions_GatewayOpCode_System_Object_"></a>SendPayloadAsync\(GatewayOpCode, object?\)

Sends a raw payload to the gateway. This method is not recommended for use unless you know what you're doing.

```csharp
[Obsolete("This method should not be used unless you know what you're doing. Instead, look towards the other explicitly implemented methods which come with client-side validation.")]
public Task SendPayloadAsync(GatewayOpCode opCode, object? data = null)
```

### Parameters

`opCode` [GatewayOpCode](DSharpPlus.Net.Abstractions.GatewayOpCode.md)

The opcode to send to the Discord gateway.

`data` [object](https://learn.microsoft.com/dotnet/api/system.object)?

The data to deserialize.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

A task representing the payload being sent.


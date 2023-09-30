# Property UdpClientFactory

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordConfiguration_UdpClientFactory"></a>UdpClientFactory

<p>Sets the factory method used to create instances of UDP clients.</p>
<p>Use <xref href="DSharpPlus.Net.Udp.DspUdpClient.CreateNew" data-throw-if-not-resolved="false"></xref> and equivalents on other implementations to switch out client implementations.</p>
<p>Defaults to <xref href="DSharpPlus.Net.Udp.DspUdpClient.CreateNew" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
public UdpClientFactoryDelegate UdpClientFactory { set; }
```

### Property Value

[UdpClientFactoryDelegate](DSharpPlus.Net.Udp.UdpClientFactoryDelegate.md)


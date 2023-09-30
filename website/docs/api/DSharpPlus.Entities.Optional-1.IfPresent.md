# Method IfPresent<TTarget\>

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_Optional_1_IfPresent__1_System_Func__0___0__"></a>IfPresent<TTarget\>\(Func<T, TTarget\>\)

Performs a mapping operation on the current <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref>, turning it into an Optional holding a
<code class="typeparamref">TTarget</code> instance if the source optional contains a value; otherwise, returns an
<xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> of that same type with no value.

```csharp
public Optional<TTarget> IfPresent<TTarget>(Func<T, TTarget> mapper)
```

### Parameters

`mapper` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<T, TTarget\>

The mapping function to apply on the current value if it exists

### Returns

[Optional](DSharpPlus.Entities.Optional\-1.md)<TTarget\>

An <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> containing a value denoted by calling <code class="paramref">mapper</code> if the current
<xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> contains a value; otherwise, an empty <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> of the target
type.

### Type Parameters

`TTarget` 

The type of the target value returned by <code class="paramref">mapper</code>


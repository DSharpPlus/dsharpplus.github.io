# Class TextInputComponent

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

A text-input field. Like selects, this can only be used once per action row.

```csharp
public sealed class TextInputComponent : DiscordComponent
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordComponent](DSharpPlus.Entities.DiscordComponent.md) ← 
[TextInputComponent](DSharpPlus.Entities.TextInputComponent.md)

###### Inherited Members

[DiscordComponent.Type](DSharpPlus.Entities.DiscordComponent.md\#DSharpPlus\_Entities\_DiscordComponent\_Type), 
[DiscordComponent.CustomId](DSharpPlus.Entities.DiscordComponent.md\#DSharpPlus\_Entities\_DiscordComponent\_CustomId)

## Constructors

### <a id="DSharpPlus_Entities_TextInputComponent__ctor"></a>TextInputComponent\(\)

```csharp
public TextInputComponent()
```

### <a id="DSharpPlus_Entities_TextInputComponent__ctor_System_String_System_String_System_String_System_String_System_Boolean_DSharpPlus_TextInputStyle_System_Int32_System_Nullable_System_Int32__"></a>TextInputComponent\(string, string, string, string, bool, TextInputStyle, int, int?\)

Constructs a new text input field.

```csharp
public TextInputComponent(string label, string customId, string placeholder = null, string value = null, bool required = true, TextInputStyle style = TextInputStyle.Short, int min_length = 0, int? max_length = null)
```

#### Parameters

`label` [string](https://learn.microsoft.com/dotnet/api/system.string)

The label for the field, placed above the input itself.

`customId` [string](https://learn.microsoft.com/dotnet/api/system.string)

The ID of this field.

`placeholder` [string](https://learn.microsoft.com/dotnet/api/system.string)

Placeholder text for the field.

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

A pre-filled value for this field.

`required` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this field is required.

`style` [TextInputStyle](DSharpPlus.TextInputStyle.md)

The style of this field. A single-ling short, or multi-line paragraph.

`min\_length` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The minimum input length.

`max\_length` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

The maximum input length. Must be greater than the minimum, if set.

## Properties

### <a id="DSharpPlus_Entities_TextInputComponent_Label"></a>Label

Label text to put above this input.

```csharp
[JsonProperty("label")]
public string Label { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_TextInputComponent_MaximumLength"></a>MaximumLength

Optional maximum length for this input. Must be a positive integer, if set.

```csharp
[JsonProperty("max_length", NullValueHandling = NullValueHandling.Ignore)]
public int? MaximumLength { get; set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_TextInputComponent_MinimumLength"></a>MinimumLength

Optional minimum length for this input.

```csharp
[JsonProperty("min_length", NullValueHandling = NullValueHandling.Ignore)]
public int MinimumLength { get; set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_TextInputComponent_Placeholder"></a>Placeholder

Optional placeholder text for this input.

```csharp
[JsonProperty("placeholder", NullValueHandling = NullValueHandling.Ignore)]
public string Placeholder { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_TextInputComponent_Required"></a>Required

Whether this input is required.

```csharp
[JsonProperty("required")]
public bool Required { get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_TextInputComponent_Style"></a>Style

Style of this input.

```csharp
[JsonProperty("style")]
public TextInputStyle Style { get; set; }
```

#### Property Value

[TextInputStyle](DSharpPlus.TextInputStyle.md)

### <a id="DSharpPlus_Entities_TextInputComponent_Value"></a>Value

Pre-filled value for this input.

```csharp
[JsonProperty("value")]
public string Value { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)


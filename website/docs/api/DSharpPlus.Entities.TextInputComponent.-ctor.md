# Constructor TextInputComponent

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_TextInputComponent__ctor"></a>TextInputComponent\(\)

```csharp
public TextInputComponent()
```

## <a id="DSharpPlus_Entities_TextInputComponent__ctor_System_String_System_String_System_String_System_String_System_Boolean_DSharpPlus_TextInputStyle_System_Int32_System_Nullable_System_Int32__"></a>TextInputComponent\(string, string, string, string, bool, TextInputStyle, int, int?\)

Constructs a new text input field.

```csharp
public TextInputComponent(string label, string customId, string placeholder = null, string value = null, bool required = true, TextInputStyle style = TextInputStyle.Short, int min_length = 0, int? max_length = null)
```

### Parameters

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


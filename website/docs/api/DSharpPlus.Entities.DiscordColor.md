# Struct DiscordColor

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a color used in Discord API.

```csharp
public struct DiscordColor
```

## Constructors

### <a id="DSharpPlus_Entities_DiscordColor__ctor_System_Int32_"></a>DiscordColor\(int\)

Creates a new color with specified value.

```csharp
public DiscordColor(int color)
```

#### Parameters

`color` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Value of the color.

### <a id="DSharpPlus_Entities_DiscordColor__ctor_System_Byte_System_Byte_System_Byte_"></a>DiscordColor\(byte, byte, byte\)

Creates a new color with specified values for red, green, and blue components.

```csharp
public DiscordColor(byte r, byte g, byte b)
```

#### Parameters

`r` [byte](https://learn.microsoft.com/dotnet/api/system.byte)

Value of the red component.

`g` [byte](https://learn.microsoft.com/dotnet/api/system.byte)

Value of the green component.

`b` [byte](https://learn.microsoft.com/dotnet/api/system.byte)

Value of the blue component.

### <a id="DSharpPlus_Entities_DiscordColor__ctor_System_Single_System_Single_System_Single_"></a>DiscordColor\(float, float, float\)

Creates a new color with specified values for red, green, and blue components.

```csharp
public DiscordColor(float r, float g, float b)
```

#### Parameters

`r` [float](https://learn.microsoft.com/dotnet/api/system.single)

Value of the red component.

`g` [float](https://learn.microsoft.com/dotnet/api/system.single)

Value of the green component.

`b` [float](https://learn.microsoft.com/dotnet/api/system.single)

Value of the blue component.

### <a id="DSharpPlus_Entities_DiscordColor__ctor_System_String_"></a>DiscordColor\(string\)

Creates a new color from specified string representation.

```csharp
public DiscordColor(string color)
```

#### Parameters

`color` [string](https://learn.microsoft.com/dotnet/api/system.string)

String representation of the color. Must be 6 hexadecimal characters, optionally with # prefix.

## Properties

### <a id="DSharpPlus_Entities_DiscordColor_Aquamarine"></a>Aquamarine

Aquamarine, or #00FFBF.

```csharp
public static DiscordColor Aquamarine { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Azure"></a>Azure

Azure, or #007FFF.

```csharp
public static DiscordColor Azure { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_B"></a>B

Gets the blue component of this color as an 8-bit integer.

```csharp
public byte B { get; }
```

#### Property Value

[byte](https://learn.microsoft.com/dotnet/api/system.byte)

### <a id="DSharpPlus_Entities_DiscordColor_Black"></a>Black

A near-black color. Due to API limitations, the color is #010101, rather than #000000, as the latter is treated as no color.

```csharp
public static DiscordColor Black { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Blue"></a>Blue

Blue, or #0000FF.

```csharp
public static DiscordColor Blue { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Blurple"></a>Blurple

Discord Blurple, or #7289DA.

```csharp
public static DiscordColor Blurple { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Brown"></a>Brown

Brown, or #A52A2A.

```csharp
public static DiscordColor Brown { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Chartreuse"></a>Chartreuse

Chartreuse, or #7FFF00.

```csharp
public static DiscordColor Chartreuse { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_CornflowerBlue"></a>CornflowerBlue

Cornflower blue, or #6495ED.

```csharp
public static DiscordColor CornflowerBlue { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Cyan"></a>Cyan

Cyan, or #00FFFF.

```csharp
public static DiscordColor Cyan { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_DarkBlue"></a>DarkBlue

Dark blue, or #00007F.

```csharp
public static DiscordColor DarkBlue { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_DarkButNotBlack"></a>DarkButNotBlack

Discord Dark, But Not Black, or #2C2F33.

```csharp
public static DiscordColor DarkButNotBlack { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_DarkGray"></a>DarkGray

Dark gray, or #A9A9A9.

```csharp
public static DiscordColor DarkGray { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_DarkGreen"></a>DarkGreen

Dark green, or #007F00.

```csharp
public static DiscordColor DarkGreen { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_DarkRed"></a>DarkRed

Dark red, or #7F0000.

```csharp
public static DiscordColor DarkRed { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_G"></a>G

Gets the green component of this color as an 8-bit integer.

```csharp
public byte G { get; }
```

#### Property Value

[byte](https://learn.microsoft.com/dotnet/api/system.byte)

### <a id="DSharpPlus_Entities_DiscordColor_Gold"></a>Gold

Gold, or #FFD700.

```csharp
public static DiscordColor Gold { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Goldenrod"></a>Goldenrod

Goldenrod, or #DAA520.

```csharp
public static DiscordColor Goldenrod { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Gray"></a>Gray

Gray, or #808080.

```csharp
public static DiscordColor Gray { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Grayple"></a>Grayple

Discord Grayple, or #99AAB5.

```csharp
public static DiscordColor Grayple { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Green"></a>Green

Green, or #00FF00.

```csharp
public static DiscordColor Green { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_HotPink"></a>HotPink

Hot pink, or #FF69B4

```csharp
public static DiscordColor HotPink { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_IndianRed"></a>IndianRed

Indian red, or #CD5C5C.

```csharp
public static DiscordColor IndianRed { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_LightGray"></a>LightGray

Light gray, or #808080.

```csharp
public static DiscordColor LightGray { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Lilac"></a>Lilac

Lilac, or #C8A2C8.

```csharp
public static DiscordColor Lilac { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Magenta"></a>Magenta

Magenta, or #FF00FF.

```csharp
public static DiscordColor Magenta { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_MidnightBlue"></a>MidnightBlue

Midnight blue, or #191970.

```csharp
public static DiscordColor MidnightBlue { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_None"></a>None

Represents no color, or integer 0;

```csharp
public static DiscordColor None { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_NotQuiteBlack"></a>NotQuiteBlack

Discord Not QuiteBlack, or #23272A.

```csharp
public static DiscordColor NotQuiteBlack { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Orange"></a>Orange

Orange, or #FFA500.

```csharp
public static DiscordColor Orange { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_PhthaloBlue"></a>PhthaloBlue

Phthalo blue, or #000F89.

```csharp
public static DiscordColor PhthaloBlue { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_PhthaloGreen"></a>PhthaloGreen

Phthalo green, or #123524.

```csharp
public static DiscordColor PhthaloGreen { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Purple"></a>Purple

Purple, or #800080.

```csharp
public static DiscordColor Purple { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_R"></a>R

Gets the red component of this color as an 8-bit integer.

```csharp
public byte R { get; }
```

#### Property Value

[byte](https://learn.microsoft.com/dotnet/api/system.byte)

### <a id="DSharpPlus_Entities_DiscordColor_Red"></a>Red

Red, or #FF0000.

```csharp
public static DiscordColor Red { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Rose"></a>Rose

Rose, or #FF007F.

```csharp
public static DiscordColor Rose { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_SapGreen"></a>SapGreen

Sap green, or #507D2A.

```csharp
public static DiscordColor SapGreen { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Sienna"></a>Sienna

Sienna, or #882D17.

```csharp
public static DiscordColor Sienna { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_SpringGreen"></a>SpringGreen

Spring green, or #00FF7F.

```csharp
public static DiscordColor SpringGreen { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Teal"></a>Teal

Teal, or #008080.

```csharp
public static DiscordColor Teal { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Turquoise"></a>Turquoise

Turquoise, or #30D5C8.

```csharp
public static DiscordColor Turquoise { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Value"></a>Value

Gets the integer representation of this color.

```csharp
public readonly int Value { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordColor_VeryDarkGray"></a>VeryDarkGray

Very dark gray, or #666666.

```csharp
public static DiscordColor VeryDarkGray { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Violet"></a>Violet

Violet, or #EE82EE.

```csharp
public static DiscordColor Violet { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Wheat"></a>Wheat

Wheat, or #F5DEB3.

```csharp
public static DiscordColor Wheat { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_White"></a>White

White, or #FFFFFF.

```csharp
public static DiscordColor White { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordColor_Yellow"></a>Yellow

Yellow, or #FFFF00.

```csharp
public static DiscordColor Yellow { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordColor_ToString"></a>ToString\(\)

Gets a string representation of this color.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

String representation of this color.

## Operators

### <a id="DSharpPlus_Entities_DiscordColor_op_Implicit_System_Int32__DSharpPlus_Entities_DiscordColor"></a>implicit operator DiscordColor\(int\)

```csharp
public static implicit operator DiscordColor(int value)
```

#### Parameters

`value` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)


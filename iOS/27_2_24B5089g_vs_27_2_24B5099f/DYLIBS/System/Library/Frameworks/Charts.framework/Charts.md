## Charts

> `/System/Library/Frameworks/Charts.framework/Charts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f1c30` | `0x2f241c` | **`+0x7ec`** |
| `__DATA.__bss` | `0xa9a0` | `0xa490` | **`-0x510`** |
| `__DATA_DIRTY.__bss` | `0xef30` | `0xf440` | **`+0x510`** |
| `__DATA_DIRTY.__data` | `0xafe8` | `0xb088` | **`+0xa0`** |
| `__DATA.__data` | `0x4ca0` | `0x4c10` | **`-0x90`** |
| `__TEXT.__cstring` | `0x2c26` | `0x2bc6` | **`-0x60`** |
| `__TEXT.__eh_frame` | `0x4490` | `0x44c0` | **`+0x30`** |
| `__DATA_DIRTY.__common` | `0x998` | `0x9a8` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x10477` | `0x10487` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xbae8` | `0xbaf4` | **`+0xc`** |
| `__AUTH_CONST.__const` | `0x1cba8` | `0x1cbb0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x71e0` | `0x71e8` | **`+0x8`** |
| `__DATA.__common` | `0x1e1` | `0x1e8` | **`+0x7`** |

### Other Changes

```diff

-8.1.5.0.0
+8.1.9.0.0

-  Functions: 12753
+  Functions: 12755

-  CStrings:  234
+  CStrings:  235
CStrings:
+ "An empty foreground style scale range has been provided. Fallback to using a default foreground style range"
+ "An empty line style scale range has been provided. Fallback to using a default line style range."
+ "An empty symbol scale range has been provided. Fallback to using a default symbol range."
+ "An empty symbol size scale range has been provided. Fallback to using a default symbol size range."
+ "Cannot match DateComponents for categorical value."
+ "Charts: %{public}s"
+ "Invalid Configuration"
+ "The automatic ScaleDomain provided to chartForegroundStyleScale contains a data type that doesn't match the chart content's domain type. Fallback to default domain."
+ "The automatic ScaleDomain provided to chartLineStyleScale contains a data type that doesn't match the chart content's domain type. Fallback to default domain."
+ "The automatic ScaleDomain provided to chartSymbolSizeScale contains a data type that doesn't match the chart content's domain type. Fallback to default domain."
+ "The domain type provided to chartForegroundStyleScale doesn't match the chart content's domain type. Fallback to default domain."
+ "The domain type provided to chartLineStyleScale doesn't match the chart content's domain type. Fallback to default domain."
+ "The domain type provided to chartSymbolSizeScale doesn't match the chart content's domain type. Fallback to default domain."
- "Charts: An empty foreground style scale range has been provided. Fallback to using a default foreground style range"
- "Charts: An empty line style scale range has been provided. Fallback to using a default line style range."
- "Charts: An empty symbol scale range has been provided. Fallback to using a default symbol range."
- "Charts: An empty symbol size scale range has been provided. Fallback to using a default symbol size range."
- "Charts: Axis values are incompatible with the data type."
- "Charts: Cannot match DateComponents for categorical value."
- "Charts: The automatic ScaleDomain provided to chartForegroundStyleScale contains a data type that doesn't match the chart content's domain type. Fallback to default domain."
- "Charts: The automatic ScaleDomain provided to chartLineStyleScale contains a data type that doesn't match the chart content's domain type. Fallback to default domain."
- "Charts: The automatic ScaleDomain provided to chartSymbolSizeScale contains a data type that doesn't match the chart content's domain type. Fallback to default domain."
- "Charts: The domain type provided to chartForegroundStyleScale doesn't match the chart content's domain type. Fallback to default domain."
- "Charts: The domain type provided to chartLineStyleScale doesn't match the chart content's domain type. Fallback to default domain."
- "Charts: The domain type provided to chartSymbolSizeScale doesn't match the chart content's domain type. Fallback to default domain."
```

## GameControllerFoundation

> `/System/Library/PrivateFrameworks/GameControllerFoundation.framework/GameControllerFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f074` | `0x6f844` | **`+0x7d0`** |
| `__AUTH_CONST.__objc_const` | `0x14928` | `0x14988` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x6afc` | `0x6b1c` | **`+0x20`** |
| `__TEXT.__cstring` | `0x7196` | `0x71a6` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x878` | `0x880` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2100` | `0x20f8` | **`-0x8`** |

### Other Changes

```diff

-14.0.14.0.0
+14.0.17.0.0

-  Functions: 2947
-  Symbols:   5354
+  Functions: 2952
+  Symbols:   5361
Symbols:
+ -[GCGenericDeviceDataInputElementAttributeExpressionModel fallbackExpression]
+ -[GCGenericDeviceDataInputElementAttributeExpressionModelBuilder fallbackExpression]
+ -[GCGenericDeviceDataInputElementAttributeExpressionModelBuilder setFallbackExpression:]
+ _OBJC_IVAR_$_GCGenericDeviceDataInputElementAttributeExpressionModel._fallbackExpression
+ _OBJC_IVAR_$_GCGenericDeviceDataInputElementAttributeExpressionModelBuilder._fallbackExpression
+ ___122-[GCGenericDeviceDataInputElementAttributeExpressionModel(Compilation) buildReactiveExpressionWithContext:consumer:error:]_block_invoke
+ ___122-[GCGenericDeviceDataInputElementAttributeExpressionModel(Compilation) buildReactiveExpressionWithContext:consumer:error:]_block_invoke_2
CStrings:
+ "<%@ %p> {\n\t identifier = %@\n\t attribute = %@\n\t fallback = %@\n}"
- "<%@ %p> {\n\t identifier = %@\n\t attribute = %@\n}"
```

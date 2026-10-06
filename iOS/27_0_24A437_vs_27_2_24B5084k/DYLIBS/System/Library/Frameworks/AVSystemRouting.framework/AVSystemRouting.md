## AVSystemRouting

> `/System/Library/Frameworks/AVSystemRouting.framework/AVSystemRouting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23394` | `0x23554` | **`+0x1c0`** |
| `__TEXT.__gcc_except_tab` | `0x2cc` | `0x300` | **`+0x34`** |
| `__AUTH_CONST.__objc_const` | `0x22a0` | `0x22c8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xe04` | `0xe24` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xd50` | `0xd58` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xbc` | `0xc0` | **`+0x4`** |

### Other Changes

```diff

-360.75.1.2.0
+385.6.1.0.0

-  Functions: 1083
-  Symbols:   932
+  Functions: 1086
+  Symbols:   938
Symbols:
+ -[AVSystemMediaSourceExtensionImpl _invalidate]
+ -[AVSystemRoute _invalidate]
+ GCC_except_table12
+ GCC_except_table15
+ GCC_except_table23
+ GCC_except_table32
+ GCC_except_table35
+ GCC_except_table39
+ GCC_except_table45
+ _OBJC_IVAR_$_AVSystemRoute._invalidated
+ _OUTLINED_FUNCTION_24
- GCC_except_table20
- GCC_except_table28
- GCC_except_table34
- GCC_except_table38
- GCC_except_table44
Functions:
~ -[AVSystemRoute addSession:] : 184 -> 192
+ -[AVSystemRoute _invalidate]
~ -[AVSystemRouteSession _invalidate] : 308 -> 328
~ -[AVSystemRoutePlaybackControl _invalidate] : 72 -> 80
+ -[AVSystemMediaSourceExtensionImpl _invalidate]
~ _OUTLINED_FUNCTION_11 : 44 -> 12
~ _OUTLINED_FUNCTION_14 : 12 -> 28
~ _OUTLINED_FUNCTION_19 : 28 -> 12
~ _OUTLINED_FUNCTION_20 : 36 -> 28
~ _OUTLINED_FUNCTION_21 : 24 -> 36
~ _OUTLINED_FUNCTION_22 : 20 -> 24
~ _OUTLINED_FUNCTION_23 : 12 -> 20
+ _OUTLINED_FUNCTION_24
~ -[AVCustomRoutingSystemControllerSystemCastingImpl _updateSystemRoutingState] : 1792 -> 1784
~ -[AVCustomRoutingSystemControllerSystemCastingImpl handleActiveClientResigned] : 292 -> 300
```

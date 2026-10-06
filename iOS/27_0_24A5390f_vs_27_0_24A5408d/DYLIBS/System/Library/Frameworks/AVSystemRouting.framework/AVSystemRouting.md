## AVSystemRouting

> `/System/Library/Frameworks/AVSystemRouting.framework/AVSystemRouting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22fdc` | `0x2326c` | **`+0x290`** |
| `__TEXT.__oslogstring` | `0x634` | `0x6a4` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x288` | `0x2cc` | **`+0x44`** |
| `__AUTH_CONST.__objc_const` | `0x2278` | `0x2298` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xdcc` | `0xdec` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x7c0` | `0x7d8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xd30` | `0xd48` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xb8` | `0xbc` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-360.70.2.0.0
+360.75.1.1.0

-  Functions: 1081
-  Symbols:   927
-  CStrings:  137
+  Functions: 1082
+  Symbols:   931
+  CStrings:  138
Symbols:
+ -[AVSystemRoute _removeFailedSession:]
+ -[AVSystemRouteSession setRoute:]
+ GCC_except_table10
+ GCC_except_table21
+ GCC_except_table22
+ GCC_except_table30
+ GCC_except_table31
+ GCC_except_table34
+ GCC_except_table38
+ GCC_except_table44
+ _OBJC_IVAR_$_AVSystemRouteSession._route
- GCC_except_table19
- GCC_except_table26
- GCC_except_table27
- GCC_except_table32
- GCC_except_table36
- GCC_except_table42
- _OUTLINED_FUNCTION_24
Functions:
~ -[AVSystemRoute addSession:] : 172 -> 184
~ -[AVSystemRoute removeSession:] : 156 -> 168
+ -[AVSystemRoute _removeFailedSession:]
+ -[AVSystemRouteSession setRoute:]
~ ___51-[AVSystemRouteSession startWithCompletionHandler:]_block_invoke : 104 -> 220
~ -[AVSystemRouteSession .cxx_destruct] : 8 -> 60
~ _OUTLINED_FUNCTION_5 : 32 -> 16
~ _OUTLINED_FUNCTION_6 : 16 -> 20
~ _OUTLINED_FUNCTION_7 : 12 -> 32
~ _OUTLINED_FUNCTION_8 : 12 -> 44
~ _OUTLINED_FUNCTION_9 : 20 -> 32
~ _OUTLINED_FUNCTION_11 : 44 -> 12
~ _OUTLINED_FUNCTION_12 : 28 -> 12
~ _OUTLINED_FUNCTION_13 : 16 -> 32
~ _OUTLINED_FUNCTION_14 : 16 -> 44
~ _OUTLINED_FUNCTION_15 : 28 -> 16
~ _OUTLINED_FUNCTION_16 : 36 -> 16
~ _OUTLINED_FUNCTION_17 : 24 -> 12
~ _OUTLINED_FUNCTION_18 : 12 -> 28
~ _OUTLINED_FUNCTION_19 : 20 -> 36
~ _OUTLINED_FUNCTION_20 : 12 -> 24
~ _OUTLINED_FUNCTION_21 : 12 -> 20
~ _OUTLINED_FUNCTION_22 : 32 -> 12
- _OUTLINED_FUNCTION_24
~ -[AVCustomRoutingSystemControllerSystemCastingImpl _handleMediaServicesReset] : 260 -> 256
~ -[AVCustomRoutingSystemControllerSystemCastingImpl _updateSystemRoutingState] : 1516 -> 1780
~ -[AVCustomRoutingSystemControllerSystemCastingImpl stopApplication] : 204 -> 200
CStrings:
+ "-AVCustomRoutingSystemController- %s: All custom protocol devices only support Real-Time Audio. Skipping event."
+ "B"
- "A"
```

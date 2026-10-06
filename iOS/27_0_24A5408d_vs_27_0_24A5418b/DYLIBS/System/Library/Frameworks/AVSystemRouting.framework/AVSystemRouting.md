## AVSystemRouting

> `/System/Library/Frameworks/AVSystemRouting.framework/AVSystemRouting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2326c` | `0x23394` | **`+0x128`** |
| `__TEXT.__oslogstring` | `0x6a4` | `0x706` | **`+0x62`** |
| `__TEXT.__cstring` | `0xc8a` | `0xcda` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xdec` | `0xe04` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x2298` | `0x22a0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x7d8` | `0x7e0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd48` | `0xd50` | **`+0x8`** |

### Other Changes

```diff

-360.75.1.1.0
+360.75.1.2.0

-  Functions: 1082
-  Symbols:   931
-  CStrings:  138
+  Functions: 1083
+  Symbols:   932
+  CStrings:  140
Symbols:
+ -[AVCustomRoutingSystemControllerSystemCastingImpl handleActiveClientResigned]
Functions:
~ _OUTLINED_FUNCTION_2 : 28 -> 24
~ _OUTLINED_FUNCTION_3 : 16 -> 28
~ _OUTLINED_FUNCTION_6 : 20 -> 16
~ _OUTLINED_FUNCTION_7 : 32 -> 20
~ _OUTLINED_FUNCTION_8 : 44 -> 32
~ _OUTLINED_FUNCTION_10 : 12 -> 44
~ _OUTLINED_FUNCTION_11 : 12 -> 44
~ _OUTLINED_FUNCTION_13 : 32 -> 12
~ _OUTLINED_FUNCTION_14 : 44 -> 12
~ _OUTLINED_FUNCTION_15 : 16 -> 32
~ _OUTLINED_FUNCTION_16 : 16 -> 32
~ _OUTLINED_FUNCTION_17 : 12 -> 16
~ _OUTLINED_FUNCTION_18 : 28 -> 16
~ _OUTLINED_FUNCTION_19 : 36 -> 28
~ _OUTLINED_FUNCTION_20 : 24 -> 36
~ _OUTLINED_FUNCTION_21 : 20 -> 24
~ _OUTLINED_FUNCTION_22 : 12 -> 20
~ _OUTLINED_FUNCTION_23 : 32 -> 12
~ -[AVCustomRoutingSystemControllerSystemCastingImpl _handleMediaServicesReset] : 256 -> 252
~ -[AVCustomRoutingSystemControllerSystemCastingImpl _sendEvent:] : 316 -> 312
~ ___63-[AVCustomRoutingSystemControllerSystemCastingImpl _sendEvent:]_block_invoke : 268 -> 264
~ -[AVCustomRoutingSystemControllerSystemCastingImpl _updateSystemRoutingState] : 1780 -> 1792
~ -[AVCustomRoutingSystemControllerSystemCastingImpl stopApplication] : 200 -> 196
~ -[AVCustomRoutingSystemControllerSystemCastingImpl setMediaSourceData:forKey:] : 280 -> 276
+ -[AVCustomRoutingSystemControllerSystemCastingImpl handleActiveClientResigned]
CStrings:
+ "-AVCustomRoutingSystemController- %s: Called. Active client resigned; relinquishing system route."
+ "-[AVCustomRoutingSystemControllerSystemCastingImpl handleActiveClientResigned]"
```

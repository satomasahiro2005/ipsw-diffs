## CryptoTokenKit

> `/System/Library/Frameworks/CryptoTokenKit.framework/CryptoTokenKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x49cdc` | `0x4977c` | **`-0x560`** |
| `__TEXT.__oslogstring` | `0x36c1` | `0x3763` | **`+0xa2`** |
| `__AUTH_CONST.__objc_const` | `0x8b60` | `0x8b20` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x1910` | `0x18e8` | **`-0x28`** |
| `__TEXT.__gcc_except_tab` | `0x14fc` | `0x14d4` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2298` | `0x2288` | **`-0x10`** |
| `__TEXT.__cstring` | `0x31a4` | `0x3194` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x594` | `0x58c` | **`-0x8`** |

### Other Changes

```diff

-867.0.0.0.2
+878.0.3.0.0

-  Functions: 2068
-  Symbols:   3695
-  CStrings:  858
+  Functions: 2066
+  Symbols:   3684
+  CStrings:  859
Symbols:
+ GCC_except_table118
+ GCC_except_table141
+ GCC_except_table15
+ GCC_except_table163
+ GCC_except_table166
+ GCC_except_table167
+ GCC_except_table174
+ GCC_except_table178
+ GCC_except_table58
+ GCC_except_table71
+ GCC_except_table90
+ _OUTLINED_FUNCTION_33
+ _OUTLINED_FUNCTION_53
+ _OUTLINED_FUNCTION_54
+ _OUTLINED_FUNCTION_57
+ _OUTLINED_FUNCTION_61
+ _OUTLINED_FUNCTION_64
- GCC_except_table123
- GCC_except_table146
- GCC_except_table16
- GCC_except_table168
- GCC_except_table171
- GCC_except_table172
- GCC_except_table179
- GCC_except_table183
- GCC_except_table29
- GCC_except_table32
- GCC_except_table41
- GCC_except_table49
- GCC_except_table76
- GCC_except_table95
- _OBJC_IVAR_$_TKSmartCardSlotManager._slotNames
- _OBJC_IVAR_$_TKSmartCardSlotManager._slotNamesQueue
- _OUTLINED_FUNCTION_35
- _OUTLINED_FUNCTION_55
- _OUTLINED_FUNCTION_56
- _OUTLINED_FUNCTION_59
- _OUTLINED_FUNCTION_62
- _OUTLINED_FUNCTION_67
- ___35-[TKSmartCardSlotManager slotNames]_block_invoke
- ___36-[TKSmartCardSlotManager slotNamed:]_block_invoke
- ___41-[TKSmartCardSlotManager setupConnection]_block_invoke_4
- ___48-[TKSmartCardSlotManager getSlotWithName:reply:]_block_invoke_2
- ___62-[TKSmartCardSlotManager setSlotWithName:endpoint:type:reply:]_block_invoke
- ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
CStrings:
+ "%{public}@: notifyWithParameters reply for client with no state request — request was torn down or replaced mid-flight (waitForStateFlushedWithReply may stall)"
```

## CryptoTokenKit

> `/System/Library/Frameworks/CryptoTokenKit.framework/CryptoTokenKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x5a0` | `0x1180` | **`+0xbe0`** |
| `__DATA_DIRTY.__objc_data` | `0x1950` | `0xd70` | **`-0xbe0`** |
| `__TEXT.__text` | `0x4977c` | `0x4a020` | **`+0x8a4`** |
| `__TEXT.__oslogstring` | `0x3763` | `0x389d` | **`+0x13a`** |
| `__TEXT.__gcc_except_tab` | `0x14d4` | `0x15ac` | **`+0xd8`** |
| `__DATA.__bss` | `0x218` | `0x278` | **`+0x60`** |
| `__DATA_DIRTY.__bss` | `0x280` | `0x220` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x18e8` | `0x1938` | **`+0x50`** |
| `__TEXT.__cstring` | `0x3194` | `0x31c4` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1878` | `0x18a8` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x5f8` | `0x620` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2288` | `0x22b0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x47f4` | `0x47fc` | **`+0x8`** |
| `__DATA.__data` | `0xe74` | `0xe78` | **`+0x4`** |

### Other Changes

```diff

-878.0.3.0.0
+878.0.8.0.0

-  Functions: 2066
-  Symbols:   3684
-  CStrings:  859
+  Functions: 2071
+  Symbols:   3695
+  CStrings:  866
Symbols:
+ -[TKSmartCardSlotEngine clientConnectionTerminated:]
+ GCC_except_table43
+ GCC_except_table49
+ GCC_except_table52
+ GCC_except_table64
+ GCC_except_table74
+ GCC_except_table82
+ GCC_except_table84
+ _OBJC_CLASS_$_NSMutableIndexSet
+ _OUTLINED_FUNCTION_45
+ _OUTLINED_FUNCTION_52
+ _OUTLINED_FUNCTION_56
+ _OUTLINED_FUNCTION_58
+ ___52-[TKSmartCardSlotEngine clientConnectionTerminated:]_block_invoke
+ ___60-[TKSmartCardSlotEngine listener:shouldAcceptNewConnection:]_block_invoke
+ ___60-[TKSmartCardSlotEngine listener:shouldAcceptNewConnection:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40s_e42_v32?0"TKSmartCardSessionRequest"8Q16^B24ls32l8s40l8
+ ___block_descriptor_48_e8_32w40w_e5_v8?0lw32l8w40l8
- GCC_except_table70
- GCC_except_table80
- _OUTLINED_FUNCTION_33
- _OUTLINED_FUNCTION_46
- _OUTLINED_FUNCTION_54
- _OUTLINED_FUNCTION_57
- _OUTLINED_FUNCTION_61
CStrings:
+ "%{public}@: client pid %d gone while holding the session, reclaiming it"
+ "%{public}@: client pid %d gone, dropping %lu queued session request(s)"
+ "%{public}@: clientConnectionTerminated for pid %d"
+ "%{public}@: session busy (held by pid %d), pid %d queued behind it (%lu waiting); notifying holder"
+ "%{public}@: session granted to pid %d (%lu still waiting)"
+ "%{public}@: session requested by pid %d (%lu now queued)"
+ "%{public}@: state reply for client with no pending request, ignoring"
+ "v32@?0@\"TKSmartCardSessionRequest\"8Q16^B24"
- "%{public}@: notifyWithParameters reply for client with no state request — request was torn down or replaced mid-flight (waitForStateFlushedWithReply may stall)"
```

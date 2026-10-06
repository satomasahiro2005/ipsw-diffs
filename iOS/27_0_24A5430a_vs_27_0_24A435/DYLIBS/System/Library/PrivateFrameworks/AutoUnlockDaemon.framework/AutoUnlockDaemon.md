## AutoUnlockDaemon

> `/System/Library/PrivateFrameworks/AutoUnlockDaemon.framework/AutoUnlockDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c1bc8` | `0x1c20dc` | **`+0x514`** |
| `__TEXT.__oslogstring` | `0x82da` | `0x835a` | **`+0x80`** |
| `__TEXT.__cstring` | `0x6fab` | `0x6feb` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x5078` | `0x5090` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1518` | `0x1528` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1dc` | `0x1ec` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x13c8` | `0x13d0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x6b0` | `0x6b8` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 7844
-  Symbols:   3370
-  CStrings:  1433
+  Functions: 7852
+  Symbols:   3374
+  CStrings:  1438
Symbols:
+ GCC_except_table118
+ GCC_except_table59
+ GCC_except_table72
+ GCC_except_table76
+ GCC_except_table99
+ _MGGetStringAnswer
+ _OBJC_CLASS_$_NIRangingAuthUWBInfo
+ ___34-[SDAutoUnlockWiFiManager uwbInfo]_block_invoke
- GCC_except_table115
- GCC_except_table69
- GCC_except_table73
- GCC_except_table96
CStrings:
+ "%s Failed to parse UWB info"
+ "%s No local UWB info"
+ "%s No remote UWB info"
+ "%s UWB decision: local=%d, remote=%d -> useUWB=%d"
+ "-[SDAutoUnlockWiFiManager _shouldUseUWBForRequest:]"
```

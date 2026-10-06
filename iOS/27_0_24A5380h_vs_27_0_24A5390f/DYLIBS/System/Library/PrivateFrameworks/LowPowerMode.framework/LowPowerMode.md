## LowPowerMode

> `/System/Library/PrivateFrameworks/LowPowerMode.framework/LowPowerMode`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5714` | `0x5828` | **`+0x114`** |
| `__TEXT.__cstring` | `0x3cd` | `0x419` | **`+0x4c`** |
| `__DATA_CONST.__const` | `0x248` | `0x270` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x340` | `0x360` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x954` | `0x96c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x468` | `0x478` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xd8` | `0xe8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x250` | `0x260` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0xc38` | `0xc40` | **`+0x8`** |

### Other Changes

```diff

-2043.0.13.502.1
+2043.0.31.0.0

-  Functions: 214
-  Symbols:   440
-  CStrings:  89
+  Functions: 217
+  Symbols:   445
+  CStrings:  91
Symbols:
+ -[_PMLowPowerMode isCurrentPowerModeUserInitiated]
+ GCC_except_table12
+ ___50-[_PMLowPowerMode isCurrentPowerModeUserInitiated]_block_invoke
+ ___50-[_PMLowPowerMode isCurrentPowerModeUserInitiated]_block_invoke_2
+ ___block_descriptor_40_e8_32r_e8_v12?0B8lr32l8
CStrings:
+ "isCurrentPowerModeUserInitiated synchronous connection failed: %@\n"
+ "v12@?0B8"
```

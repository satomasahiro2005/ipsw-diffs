## PersonalAudio

> `/System/Library/PrivateFrameworks/PersonalAudio.framework/PersonalAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14098` | `0x144fc` | **`+0x464`** |
| `__TEXT.__oslogstring` | `0xdb8` | `0xe2e` | **`+0x76`** |
| `__AUTH_CONST.__objc_const` | `0x1078` | `0x10d8` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x6d0` | `0x720` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xee8` | `0xf30` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0xef0` | `0xf28` | **`+0x38`** |
| `__DATA.__bss` | `0xa8` | `0xd8` | **`+0x30`** |
| `__DATA_DIRTY.__bss` | `0xc0` | `0x90` | **`-0x30`** |
| `__DATA.__objc_ivar` | `0xac` | `0xb4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x578` | `0x580` | **`+0x8`** |
| `__TEXT.__cstring` | `0x1283` | `0x1285` | **`+0x2`** |

### Other Changes

```diff

-543.2.1.0.0
+543.2.3.0.0

-  Functions: 409
-  Symbols:   751
-  CStrings:  280
+  Functions: 418
+  Symbols:   763
+  CStrings:  282
Symbols:
+ -[PAAccessoryManager lastSentTransparencyDataByAddress]
+ -[PAAccessoryManager pseHysteresisTimer]
+ -[PAAccessoryManager sendUpdateToAccessoryCoalesced]
+ -[PAAccessoryManager sendUpdateToAccessoryForcingWrite:]
+ -[PAAccessoryManager setLastSentTransparencyDataByAddress:]
+ -[PAAccessoryManager setPseHysteresisTimer:]
+ GCC_except_table115
+ GCC_except_table173
+ GCC_except_table174
+ GCC_except_table229
+ GCC_except_table240
+ GCC_except_table251
+ GCC_except_table311
+ GCC_except_table326
+ GCC_except_table348
+ GCC_except_table389
+ GCC_except_table399
+ GCC_except_table402
+ GCC_except_table405
+ GCC_except_table50
+ GCC_except_table68
+ GCC_except_table77
+ _OBJC_IVAR_$_PAAccessoryManager._lastSentTransparencyDataByAddress
+ _OBJC_IVAR_$_PAAccessoryManager._pseHysteresisTimer
+ ___52-[PAAccessoryManager sendUpdateToAccessoryCoalesced]_block_invoke
+ ___52-[PAAccessoryManager sendUpdateToAccessoryCoalesced]_block_invoke_2
+ ___56-[PAAccessoryManager sendUpdateToAccessoryForcingWrite:]_block_invoke
+ ___56-[PAAccessoryManager sendUpdateToAccessoryForcingWrite:]_block_invoke_2
+ ___56-[PAAccessoryManager sendUpdateToAccessoryForcingWrite:]_block_invoke_3
+ ___56-[PAAccessoryManager sendUpdateToAccessoryForcingWrite:]_block_invoke_4
+ ___block_descriptor_48_e8_32s40w_e5_v8?0lw40l8s32l8
+ ___block_descriptor_57_e8_32s40s48s_e17_v16?0"NSArray"8ls32l8s40l8s48l8
+ ___block_descriptor_57_e8_32s40s48s_e25_v32?0"NSString"8Q16^B24ls32l8s40l8s48l8
+ ___block_descriptor_66_e8_32s40s48s56s_e8_v12?0B8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_66_e8_32s40s48s56s_e8_v16?0Q8ls32l8s40l8s48l8s56l8
- GCC_except_table106
- GCC_except_table164
- GCC_except_table165
- GCC_except_table220
- GCC_except_table231
- GCC_except_table242
- GCC_except_table302
- GCC_except_table317
- GCC_except_table339
- GCC_except_table380
- GCC_except_table390
- GCC_except_table393
- GCC_except_table396
- GCC_except_table46
- GCC_except_table60
- GCC_except_table69
- ___43-[PAAccessoryManager sendUpdateToAccessory]_block_invoke
- ___43-[PAAccessoryManager sendUpdateToAccessory]_block_invoke_2
- ___43-[PAAccessoryManager sendUpdateToAccessory]_block_invoke_3
- ___43-[PAAccessoryManager sendUpdateToAccessory]_block_invoke_4
- ___block_descriptor_48_e8_32s40s_e25_v32?0"NSString"8Q16^B24ls32l8s40l8
- ___block_descriptor_57_e8_32s40s48s_e8_v12?0B8ls32l8s40l8s48l8
- ___block_descriptor_57_e8_32s40s48s_e8_v16?0Q8ls32l8s40l8s48l8
CStrings:
+ "PAAccessoryManager: Skipping transparency update because pending timer"
+ "Skipping update to %@, configuration unchanged"
```

## PersonalAudio

> `/System/Library/PrivateFrameworks/PersonalAudio.framework/PersonalAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13f94` | `0x14098` | **`+0x104`** |
| `__TEXT.__cstring` | `0x1253` | `0x1283` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x1500` | `0x1520` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xec8` | `0xee8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xed8` | `0xef0` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x1088` | `0x1078` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x568` | `0x578` | **`+0x10`** |
| `__DATA.__bss` | `0xe0` | `0xd8` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x88` | `0x90` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xb0` | `0xac` | **`-0x4`** |

### Other Changes

```diff

-530.0.0.0.0
+534.0.0.0.0

-  Functions: 406
-  Symbols:   749
-  CStrings:  279
+  Functions: 409
+  Symbols:   751
+  CStrings:  280
Symbols:
+ -[PADatabaseManager shouldExcludeStoreFromCloudBackup]
+ -[PASettings personalMediaAutomationSkipRouteCheck]
+ -[PASettings setPersonalMediaAutomationSkipRouteCheck:]
+ -[PAStimulus rampTowardTarget:]
+ GCC_except_table164
+ GCC_except_table165
+ GCC_except_table220
+ GCC_except_table231
+ GCC_except_table242
+ GCC_except_table302
+ GCC_except_table317
+ GCC_except_table339
+ GCC_except_table380
+ GCC_except_table390
+ GCC_except_table393
+ GCC_except_table396
+ _OBJC_IVAR_$_PAStimulus._state
+ ___31-[PAStimulus rampTowardTarget:]_block_invoke
+ ___block_descriptor_57_e8_32s_e5_v8?0ls32l8
- -[PAStimulus rampVolumeUp:]
- GCC_except_table162
- GCC_except_table163
- GCC_except_table218
- GCC_except_table229
- GCC_except_table240
- GCC_except_table300
- GCC_except_table315
- GCC_except_table337
- GCC_except_table378
- GCC_except_table388
- GCC_except_table391
- GCC_except_table394
- _OBJC_IVAR_$_PAStimulus._ramping
- _OBJC_IVAR_$_PAStimulus._rampingUp
- ___27-[PAStimulus rampVolumeUp:]_block_invoke
- ___block_descriptor_41_e8_32s_e5_v8?0ls32l8
CStrings:
+ "PersonalMediaAutomationSkipRouteCheckPreference"
```

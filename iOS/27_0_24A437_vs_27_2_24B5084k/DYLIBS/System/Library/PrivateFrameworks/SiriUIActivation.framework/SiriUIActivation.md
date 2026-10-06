## SiriUIActivation

> `/System/Library/PrivateFrameworks/SiriUIActivation.framework/SiriUIActivation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f470` | `0x2f7b4` | **`+0x344`** |
| `__TEXT.__cstring` | `0x4c5b` | `0x4d5b` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x4e2b` | `0x4edb` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x8e0` | `0x920` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fe8` | `0x2020` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x26e8` | `0x2720` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x2938` | `0x2968` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x5d0` | `0x5d8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xde0` | `0xde8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1bc` | `0x1c0` | **`+0x4`** |

### Other Changes

```diff

-3600.55.37.11.4
+3605.22.2.0.0

-  Functions: 1077
-  Symbols:   1659
-  CStrings:  623
+  Functions: 1082
+  Symbols:   1666
+  CStrings:  631
Symbols:
+ -[SASUICampoSessionCoordinator initWithResumptionGracePeriod:]
+ -[SASUICampoSessionCoordinator init]
+ -[SASUICampoSessionCoordinator resumptionGracePeriod]
+ -[SiriPresentationViewController _isForPreprocessedCarPlayBannerTap:newSiriRequestOptions:]
+ -[SiriPresentationViewController noteWillBeginTearDownForDismissalReason:withOriginalDismissalOptions:]
+ GCC_except_table100
+ GCC_except_table105
+ GCC_except_table108
+ GCC_except_table121
+ GCC_except_table122
+ GCC_except_table128
+ GCC_except_table132
+ GCC_except_table141
+ GCC_except_table147
+ GCC_except_table156
+ GCC_except_table171
+ GCC_except_table176
+ GCC_except_table197
+ GCC_except_table221
+ GCC_except_table222
+ GCC_except_table230
+ GCC_except_table231
+ GCC_except_table251
+ GCC_except_table277
+ GCC_except_table278
+ GCC_except_table285
+ GCC_except_table290
+ GCC_except_table306
+ GCC_except_table314
+ GCC_except_table34
+ GCC_except_table37
+ GCC_except_table44
+ GCC_except_table46
+ GCC_except_table53
+ GCC_except_table58
+ GCC_except_table61
+ GCC_except_table64
+ GCC_except_table74
+ GCC_except_table77
+ GCC_except_table82
+ GCC_except_table91
+ GCC_except_table93
+ GCC_except_table95
+ _OBJC_CLASS_$_SISchemaUEICarPlayBannerPreprocessedTapped
+ _OBJC_IVAR_$_SASUICampoSessionCoordinator._resumptionGracePeriod
+ ___block_descriptor_65_e8_32s40s48s56w_e20_v20?0B8"NSError"12lw56l8s32l8s40l8s48l8
- GCC_except_table104
- GCC_except_table106
- GCC_except_table118
- GCC_except_table119
- GCC_except_table126
- GCC_except_table130
- GCC_except_table131
- GCC_except_table145
- GCC_except_table154
- GCC_except_table169
- GCC_except_table174
- GCC_except_table193
- GCC_except_table217
- GCC_except_table220
- GCC_except_table228
- GCC_except_table229
- GCC_except_table249
- GCC_except_table275
- GCC_except_table276
- GCC_except_table283
- GCC_except_table288
- GCC_except_table300
- GCC_except_table312
- GCC_except_table33
- GCC_except_table36
- GCC_except_table43
- GCC_except_table45
- GCC_except_table52
- GCC_except_table57
- GCC_except_table59
- GCC_except_table62
- GCC_except_table72
- GCC_except_table76
- GCC_except_table81
- GCC_except_table90
- GCC_except_table92
- GCC_except_table94
- GCC_except_table99
- ___block_descriptor_49_e8_32s40w_e20_v20?0B8"NSError"12lw40l8s32l8
CStrings:
+ "%s #Campo Resumption grace period is %f seconds"
+ "%s #Preprocessing #CarPlay emitting preprocessed banner tapped event."
+ "%s #Preprocessing #CarPlay isForPreprocessedCarPlayBannerTap %d"
+ "-[SASUICampoSessionCoordinator initWithResumptionGracePeriod:]"
+ "-[SiriPresentationViewController _isForPreprocessedCarPlayBannerTap:newSiriRequestOptions:]"
+ "-[SiriPresentationViewController _startRequestWithOptions:]_block_invoke_2"
+ "com.apple.campo"
+ "sessionResumptionTimeout"
```

## StickerKit

> `/System/Library/Frameworks/StickerKit.framework/StickerKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2504a0` | `0x256bfc` | **`+0x675c`** |
| `__TEXT.__eh_frame` | `0xdd70` | `0xdfc8` | **`+0x258`** |
| `__AUTH_CONST.__const` | `0xf698` | `0xf8c0` | **`+0x228`** |
| `__TEXT.__const` | `0x13974` | `0x13b54` | **`+0x1e0`** |
| `__DATA.__bss` | `0x10f10` | `0x11090` | **`+0x180`** |
| `__AUTH_CONST.__objc_const` | `0x2d6d0` | `0x2d848` | **`+0x178`** |
| `__TEXT.__oslogstring` | `0x5eaf` | `0x5fff` | **`+0x150`** |
| `__TEXT.__constg_swiftt` | `0xb4c8` | `0xb60c` | **`+0x144`** |
| `__TEXT.__swift5_reflstr` | `0x6935` | `0x6a55` | **`+0x120`** |
| `__TEXT.__swift5_fieldmd` | `0x6604` | `0x66f8` | **`+0xf4`** |
| `__AUTH.__objc_data` | `0x9540` | `0x9630` | **`+0xf0`** |
| `__DATA_DIRTY.__data` | `0x1b90` | `0x1c80` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x82b0` | `0x83a0` | **`+0xf0`** |
| `__TEXT.__swift5_capture` | `0x4334` | `0x43fc` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x449c` | `0x454c` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0xe1f2` | `0xe290` | **`+0x9e`** |
| `__AUTH.__data` | `0x7270` | `0x7300` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x7c80` | `0x7ce8` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x49b0` | `0x49f0` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x9d0` | `0xa0c` | **`+0x3c`** |
| `__AUTH_CONST.__auth_got` | `0x2c90` | `0x2cc0` | **`+0x30`** |
| `__DATA.__data` | `0x7230` | `0x7260` | **`+0x30`** |
| `__DATA_DIRTY.__objc_data` | `0x2068` | `0x2098` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x47c` | `0x498` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x7b0` | `0x7c8` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0xc50` | `0xc68` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x990` | `0x9a0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x66c` | `0x678` | **`+0xc`** |
| `__DATA.__common` | `0x4a0` | `0x4a8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x17c0` | `0x17b8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x6a8` | `0x6b0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x4e4` | `0x4ec` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0xcc` | `0xd0` | **`+0x4`** |

### Other Changes

```diff

-138.0.0.0.0
+142.0.0.0.0

-  Functions: 11104
-  Symbols:   5002
-  CStrings:  965
+  Functions: 11190
+  Symbols:   5019
+  CStrings:  974
Symbols:
+ _CFPreferencesAppSynchronize
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_CLASS_$_STKStickerCreationTrackerSPI
+ _OBJC_METACLASS_$_STKStickerCreationTrackerSPI
+ __CLASS_METHODS_STKStickerCreationTrackerSPI
+ __DATA_STKStickerCreationTrackerSPI
+ __INSTANCE_METHODS_STKStickerCreationTrackerSPI
+ __METACLASS_DATA_STKStickerCreationTrackerSPI
+ ___swift_closure_destructor.152Tm
+ ___swift_closure_destructor.180Tm
+ ___swift_closure_destructor.200Tm
+ ___swift_closure_destructor.204Tm
+ ___swift_closure_destructor.226Tm
+ ___swift_closure_destructor.281Tm
+ ___swift_closure_destructor.300Tm
+ ___swift_closure_destructor.398Tm
+ ___swift_closure_destructor.402Tm
+ ___swift_closure_destructor.410Tm
+ ___swift_closure_destructor.488Tm
+ ___swift_closure_destructor.86Tm
+ ___swift_memcpy208_8
+ ___swift_memcpy49_8
+ ___unnamed_20
+ _associated conformance 10StickerKit0A15CreationTrackerV13AnimationTypeOSHAASQ
+ _symbolic $s10StickerKit24RecencyGenerationReadingP
+ _symbolic Say_____GSg 8Stickers7StickerC
+ _symbolic Say_____GSgIeAgHr_ 8Stickers7StickerC
+ _symbolic _____ 10StickerKit0A15CreationTrackerV13AnimationTypeO
+ _symbolic _____ 10StickerKit28STKStickerCreationTrackerSPIC
+ _symbolic _____ 10StickerKit33ProductionRecencyGenerationReaderV
+ _symbolic ______p 10StickerKit24RecencyGenerationReadingP
+ _symbolic _____ySS_____G s18_DictionaryStorageC 10StickerKit10ImageGlyphC
+ _symbolic _____y_SiG 10StickerKit33UnifiedRecentImageGlyphDataSourceC6AtomicC
+ _symbolic _____y______ySb_GG 7Combine10PublishersO4DropV AA9PublishedV9PublisherV
+ _symbolic _____y______y______ySb_GGG 7Combine10PublishersO16RemoveDuplicatesV AC4DropV AA9PublishedV9PublisherV
- ___swift_closure_destructor.139Tm
- ___swift_closure_destructor.174Tm
- ___swift_closure_destructor.183Tm
- ___swift_closure_destructor.187Tm
- ___swift_closure_destructor.220Tm
- ___swift_closure_destructor.261Tm
- ___swift_closure_destructor.279Tm
- ___swift_closure_destructor.375Tm
- ___swift_closure_destructor.379Tm
- ___swift_closure_destructor.387Tm
- ___swift_closure_destructor.460Tm
- ___swift_closure_destructor.78Tm
- ___swift_memcpy168_8
- ___unnamed_18
- _swift_initStaticObject
- _swift_retain_x9
- _symbolic Say_____GIeAgHr_ 8Stickers7StickerC
- _symbolic _____Sg 8Stickers12StickerStoreC
CStrings:
+ "Recents gen+order read: generation=%ld orderCount=%ld synchronize=%lluus"
+ "Recents preview shown: prefsToken=%ld, appliedVersion=%ld, previewCount=%ld"
+ "Recents restore: cachedToken=%ld, stale=%{bool}d"
+ "Recents reveal fired (token %ld)"
+ "Recents withhold (no order): prefsToken=%ld, appliedVersion=%ld"
+ "STKStickerCreationTrackerDidChange"
+ "com.apple.stickers.recency.generation"
+ "com.apple.stickers.recency.order"
+ "recentsGeneration"
```

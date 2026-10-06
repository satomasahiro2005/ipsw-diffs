## MediaSuggester

> `/System/Library/PrivateFrameworks/MediaSuggester.framework/MediaSuggester`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7d184` | `0x80c4c` | **`+0x3ac8`** |
| `__TEXT.__eh_frame` | `0x33c4` | `0x3674` | **`+0x2b0`** |
| `__AUTH_CONST.__const` | `0x5bf0` | `0x59c0` | **`-0x230`** |
| `__TEXT.__cstring` | `0x1ea4` | `0x2004` | **`+0x160`** |
| `__TEXT.__swift5_capture` | `0x1d1c` | `0x1c54` | **`-0xc8`** |
| `__TEXT.__unwind_info` | `0x1e98` | `0x1f38` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x23ec` | `0x239c` | **`-0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xb48` | `0xb88` | **`+0x40`** |
| `__DATA.__data` | `0xf10` | `0xf38` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x5e0` | `0x608` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x240` | `0x264` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0xc30` | `0xc48` | **`+0x18`** |
| `__TEXT.__const` | `0x3780` | `0x3790` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x190c` | `0x191a` | **`+0xe`** |
| `__TEXT.__swift_as_ret` | `0x144` | `0x148` | **`+0x4`** |

### Other Changes

```diff

-85.0.0.0.0
+87.0.1.0.0

-  Functions: 3792
-  Symbols:   337
-  CStrings:  381
+  Functions: 3796
+  Symbols:   340
+  CStrings:  391
Symbols:
+ _OBJC_CLASS_$_NSCompoundPredicate
+ _OBJC_CLASS_$_NSPredicate
+ _swift_release_x12
CStrings:
+ "MSBiomeMediaReader.playMediaAppEntities: Full enumeration complete - Entities: %ld, Bundles: %ld"
+ "americanFootball"
+ "australianFootball"
+ "crossCountrySkiing"
+ "danceInspiredTraining"
+ "equestrianSports"
+ "functionalStrengthTraining"
+ "mixedMetabolicCardioTraining"
+ "preparationAndRecovery"
+ "underwaterDiving"
+ "wheelchairRunPace"
+ "wheelchairWalkPace"
- "MSBiomeMediaReader.playMediaAppEntities: Full enumeration complete - Added: %ld, Removed: %ld, Bundles: %ld"
- "MSBiomeMediaReader.playMediaAppEntities: ⚠️ Ignoring %ld removed items"
```

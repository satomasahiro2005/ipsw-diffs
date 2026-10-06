## TipsCore

> `/System/Library/PrivateFrameworks/TipsCore.framework/TipsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__objc_data` | `0x23c8` | `0x43f0` | **`+0x2028`** |
| `__AUTH.__objc_data` | `0x26d8` | `0x6c0` | **`-0x2018`** |
| `__TEXT.__text` | `0xb1264` | `0xb1c70` | **`+0xa0c`** |
| `__DATA_DIRTY.__data` | `0x7d8` | `0x11c8` | **`+0x9f0`** |
| `__AUTH.__data` | `0x990` | `0xa0` | **`-0x8f0`** |
| `__DATA.__bss` | `0x2990` | `0x2a90` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x3a10` | `0x3ae0` | **`+0xd0`** |
| `__DATA.__data` | `0x1370` | `0x12c0` | **`-0xb0`** |
| `__TEXT.__const` | `0x2a64` | `0x2ae4` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0xf6c` | `0xfdc` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x22b0` | `0x2308` | **`+0x58`** |
| `__TEXT.__swift5_reflstr` | `0x1222` | `0x1272` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x33f0` | `0x3438` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0xe7e0` | `0xe820` | **`+0x40`** |
| `__TEXT.__cstring` | `0x4fb3` | `0x4ff3` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x1948` | `0x1910` | **`-0x38`** |
| `__TEXT.__swift5_assocty` | `0x228` | `0x258` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x950` | `0x978` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x8b40` | `0x8b68` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0xfbc` | `0xfe0` | **`+0x24`** |
| `__TEXT.__swift5_fieldmd` | `0x10dc` | `0x10f4` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d18` | `0x3d28` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x18e4` | `0x18f4` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x160` | `0x168` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x7c8` | `0x7cc` | **`+0x4`** |

### Other Changes

```diff

-853.0.0.0.0
+855.0.0.0.0

+  - /usr/lib/swift/libswiftCompression.dylib

-  Functions: 5381
-  Symbols:   5783
-  CStrings:  1121
+  Functions: 5398
+  Symbols:   5793
+  CStrings:  1123
Symbols:
+ -[TPSDataCache init]
+ GCC_except_table52
+ _OBJC_IVAR_$_TPSDataCache._lock
+ ___block_descriptor_56_e8_32s40r48r_e5_v8?0lr40l8s32l8r48l8
+ ___block_descriptor_56_e8_32s40r_e5_v8?0ls32l8r40l8
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCompression_$_TipsCore
+ _associated conformance 8TipsCore36TPSAnalyticsEventLearnMoreUsedSearchC14SelectedOptionOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 8TipsCore39TPSAnalyticsEventLearnMoreContentViewedC10ViewSourceOs12CaseIterableAA8AllCasessAFP_Sl
+ _symbolic Say_____G 8TipsCore36TPSAnalyticsEventLearnMoreUsedSearchC14SelectedOptionO
+ _symbolic Say_____G 8TipsCore39TPSAnalyticsEventLearnMoreContentViewedC10ViewSourceO
- GCC_except_table51
CStrings:
+ "D"
+ "TPSForceSignificantChangeSheet"
+ "TPSUsesOfflineLearnMoreContent"
- "4"
```

## TipsCore

> `/System/Library/PrivateFrameworks/TipsCore.framework/TipsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb290c` | `0xb3350` | **`+0xa44`** |
| `__AUTH_CONST.__const` | `0x3fc0` | `0x4050` | **`+0x90`** |
| `__DATA.__bss` | `0x2a90` | `0x2b10` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x1178` | `0x11c8` | **`+0x50`** |
| `__TEXT.__const` | `0x2af4` | `0x2b44` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x1272` | `0x12a2` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x3440` | `0x3470` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x5480` | `0x5460` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x2328` | `0x2340` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x258` | `0x270` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0xe8b0` | `0xe8c0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x10f4` | `0x1100` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x980` | `0x978` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d38` | `0x3d40` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x43f0` | `0x43f8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x18f4` | `0x18fc` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x1910` | `0x1908` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x8bb8` | `0x8bc0` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x1004` | `0x100a` | **`+0x6`** |
| `__TEXT.__swift5_proto` | `0x168` | `0x16c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-857.0.0.0.0
+866.0.0.0.0

+  - /System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels

+  - /System/Library/PrivateFrameworks/ModelCatalog.framework/ModelCatalog

+  - /usr/lib/swift/libswiftAccelerate.dylib

+  - /usr/lib/swift/libswiftCoreAudio.dylib

+  - /usr/lib/swift/libswiftQuartzCore.dylib

-  Functions: 5407
-  Symbols:   5810
+  Functions: 5422
+  Symbols:   5817
Symbols:
+ +[NSLocale(TPSCoreAdditions) tps_userPreferredLocalizationsFromArray:forLanguages:]
+ GCC_except_table59
+ GCC_except_table74
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftAccelerate_$_TipsCore
+ __swift_FORCE_LOAD_$_swiftCoreAudio
+ __swift_FORCE_LOAD_$_swiftCoreAudio_$_TipsCore
+ __swift_FORCE_LOAD_$_swiftQuartzCore
+ __swift_FORCE_LOAD_$_swiftQuartzCore_$_TipsCore
+ _associated conformance 8TipsCore28LearnMoreAnalyticsControllerC13SessionActionOs12CaseIterableAA8AllCasessAFP_Sl
+ _symbolic Say_____G 8TipsCore28LearnMoreAnalyticsControllerC13SessionActionO
- +[TPSCommonDefines siriCollectionIdentifier]
- GCC_except_table75
- GCC_except_table82
- _symbolic _____Sg_ABt 10Foundation4DateV
CStrings:
+ "TPSUserGuidePreferredLanguage"
+ "com.apple.learnmore.content_viewed"
+ "com.apple.learnmore.session"
+ "com.apple.learnmore.used_search"
- "Siri"
- "com.apple.tips.learnmore.content_viewed"
- "com.apple.tips.learnmore.session"
- "com.apple.tips.learnmore.used_search"
```

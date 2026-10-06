## TipsCore

> `/System/Library/PrivateFrameworks/TipsCore.framework/TipsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb1c70` | `0xb290c` | **`+0xc9c`** |
| `__AUTH_CONST.__const` | `0x3ae0` | `0x3fc0` | **`+0x4e0`** |
| `__AUTH_CONST.__objc_const` | `0xe820` | `0xe8b0` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x5420` | `0x5480` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x6c0` | `0x710` | **`+0x50`** |
| `__TEXT.__cstring` | `0x4ff3` | `0x5043` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x8b68` | `0x8bb8` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0xfe0` | `0x1004` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0x1158` | `0x1178` | **`+0x20`** |
| `__DATA.__data` | `0x12c0` | `0x12e0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2308` | `0x2328` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d28` | `0x3d38` | **`+0x10`** |
| `__TEXT.__const` | `0x2ae4` | `0x2af4` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x978` | `0x980` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x510` | `0x518` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x328` | `0x330` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3438` | `0x3440` | **`+0x8`** |

### Other Changes

```diff

-855.0.0.0.0
+857.0.0.0.0

-  Functions: 5398
-  Symbols:   5793
-  CStrings:  1123
+  Functions: 5407
+  Symbols:   5810
+  CStrings:  1127
Symbols:
+ +[TPSCommonDefines siriCollectionIdentifier]
+ -[TPSContextualBiomeDormancyUserInteractionEvent _filteringPredicate]
+ -[TPSContextualBiomeDormancyUserInteractionEvent filterHandler]
+ -[TPSContextualBiomeDormancyUserInteractionEvent filterParametersForBiomeQuery]
+ -[TPSContextualBiomeDormancyUserInteractionEvent publisherFromStartTime:]
+ GCC_except_table75
+ GCC_except_table82
+ _OBJC_CLASS_$_TPSContextualBiomeDormancyUserInteractionEvent
+ _OBJC_METACLASS_$_TPSContextualBiomeDormancyUserInteractionEvent
+ _TPSContextualBiomeDormancyFeatureUserInteractionStream
+ __OBJC_$_CLASS_METHODS_TPSCommonDefines(TipsCore|TipsCore1)
+ __OBJC_$_INSTANCE_METHODS_TPSContextualBiomeDormancyUserInteractionEvent
+ __OBJC_CLASS_RO_$_TPSContextualBiomeDormancyUserInteractionEvent
+ __OBJC_METACLASS_RO_$_TPSContextualBiomeDormancyUserInteractionEvent
+ _kDormancyUserInteractionBundleID
+ _kDormancyUserInteractionEventType
+ _kDormancyUserInteractionFeature
+ _symbolic SS_SaySSGt
+ _symbolic _____Sg 10Foundation6LocaleV6RegionV
+ _symbolic _____ySSSaySSGG s18_DictionaryStorageC
- GCC_except_table59
- GCC_except_table74
- __OBJC_$_CLASS_METHODS_TPSCommonDefines(TipsCore)
CStrings:
+ "Dormancy.Feature.UserInteraction"
+ "Siri"
+ "User guide languages: "
+ "eventType"
```

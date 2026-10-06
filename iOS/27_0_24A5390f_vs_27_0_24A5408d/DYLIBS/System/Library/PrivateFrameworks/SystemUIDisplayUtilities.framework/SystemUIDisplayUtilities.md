## SystemUIDisplayUtilities

> `/System/Library/PrivateFrameworks/SystemUIDisplayUtilities.framework/SystemUIDisplayUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xabe4` | `0xb538` | **`+0x954`** |
| `__AUTH_CONST.__objc_const` | `0xf78` | `0x1158` | **`+0x1e0`** |
| `__TEXT.__objc_methlist` | `0x770` | `0x818` | **`+0xa8`** |
| `__DATA_CONST.__const` | `0x2b0` | `0x328` | **`+0x78`** |
| `__TEXT.__cstring` | `0x6ab` | `0x70b` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xbeb` | `0xc4b` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x388` | `0x3d8` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x6a8` | `0x6e8` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3e0` | `0x408` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x578` | `0x598` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x84` | `0xa0` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x498` | `0x4b0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x108` | `0x120` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x190` | `0x198` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x60` | `0x68` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x30` | `0x38` | **`+0x8`** |

### Other Changes

```diff

-102.0.0.0.0
+104.100.0.0.0

-  Functions: 287
-  Symbols:   556
-  CStrings:  78
+  Functions: 303
+  Symbols:   587
+  CStrings:  80
Symbols:
+ -[SDUDisplayBlankingDescription .cxx_destruct]
+ -[SDUDisplayBlankingDescription blankingState]
+ -[SDUDisplayBlankingDescription bundleIDs]
+ -[SDUDisplayBlankingDescription initWithRegionIdentifier:blankingState:bundleIDs:previousBlankingState:previousBundleIDs:]
+ -[SDUDisplayBlankingDescription previousBlankingState]
+ -[SDUDisplayBlankingDescription previousBundleIDs]
+ -[SDUDisplayBlankingDescription regionIdentifier]
+ -[SDUDisplayRegionBlankingController _liveBundleIDs]
+ -[SDUDisplayRegionBlankingController _waitForPendingDeliveries]
+ -[SDUDisplayRegionBlankingCoordinator blankingStateUpdated:]
+ _BSEqualArrays
+ _OBJC_CLASS_$_SDUDisplayBlankingDescription
+ _OBJC_IVAR_$_SDUDisplayBlankingDescription._blankingState
+ _OBJC_IVAR_$_SDUDisplayBlankingDescription._bundleIDs
+ _OBJC_IVAR_$_SDUDisplayBlankingDescription._previousBlankingState
+ _OBJC_IVAR_$_SDUDisplayBlankingDescription._previousBundleIDs
+ _OBJC_IVAR_$_SDUDisplayBlankingDescription._regionIdentifier
+ _OBJC_IVAR_$_SDUDisplayRegionBlankingController._blankingBundleIDs
+ _OBJC_IVAR_$_SDUDisplayRegionBlankingController._connectionQueue
+ _OBJC_METACLASS_$_SDUDisplayBlankingDescription
+ __OBJC_$_INSTANCE_METHODS_SDUDisplayBlankingDescription
+ __OBJC_$_INSTANCE_VARIABLES_SDUDisplayBlankingDescription
+ __OBJC_$_PROP_LIST_SDUDisplayBlankingDescription
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SDUDisplayRegionBlankingObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SDUDisplayRegionBlankingRenderer
+ __OBJC_CLASS_RO_$_SDUDisplayBlankingDescription
+ __OBJC_METACLASS_RO_$_SDUDisplayBlankingDescription
+ ___60-[SDUDisplayRegionBlankingCoordinator blankingStateUpdated:]_block_invoke
+ ___60-[SDUDisplayRegionBlankingCoordinator blankingStateUpdated:]_block_invoke_2
+ ___63-[SDUDisplayRegionBlankingController _waitForPendingDeliveries]_block_invoke
+ ___block_descriptor_40_e8_32bs_e8_v16?0Q8ls32l8
+ ___block_descriptor_48_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ _dispatch_sync
+ _objc_retain_x28
- -[SDUDisplayRegionBlankingCoordinator setBlankingState:ofDisplayRegion:forBundleIDs:]
- GCC_except_table3
- ___85-[SDUDisplayRegionBlankingCoordinator setBlankingState:ofDisplayRegion:forBundleIDs:]_block_invoke
- ___85-[SDUDisplayRegionBlankingCoordinator setBlankingState:ofDisplayRegion:forBundleIDs:]_block_invoke_2
CStrings:
+ "$"
+ "SDUDisplayRegionBlankingCoordinator: '%@' region bundle IDs changed while blanked: (%@)"
+ "a"
+ "com.apple.SystemUIDisplayUtilities.SDUDisplayRegionBlankingControllerDelegate.connectionQueue"
- "\""
- "A"
```

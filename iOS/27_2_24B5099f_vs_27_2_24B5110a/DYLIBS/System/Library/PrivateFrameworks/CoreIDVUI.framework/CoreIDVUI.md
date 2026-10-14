## CoreIDVUI

> `/System/Library/PrivateFrameworks/CoreIDVUI.framework/CoreIDVUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2828bc` | `0x284364` | **`+0x1aa8`** |
| `__AUTH_CONST.__const` | `0xefe8` | `0xf168` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0x10082` | `0x101d2` | **`+0x150`** |
| `__TEXT.__eh_frame` | `0x13a94` | `0x13b9c` | **`+0x108`** |
| `__DATA.__data` | `0x5bec` | `0x5cac` | **`+0xc0`** |
| `__DATA_CONST.__got` | `0x21d8` | `0x2250` | **`+0x78`** |
| `__DATA.__bss` | `0xb980` | `0xb910` | **`-0x70`** |
| `__TEXT.__const` | `0x14b34` | `0x14ba4` | **`+0x70`** |
| `__AUTH.__data` | `0x99d0` | `0x9970` | **`-0x60`** |
| `__TEXT.__swift5_capture` | `0x373c` | `0x3784` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x88c0` | `0x8908` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x633c` | `0x6370` | **`+0x34`** |
| `__TEXT.__swift5_reflstr` | `0x7a1c` | `0x7a4c` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0xd598` | `0xd5b8` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0xeb8` | `0xea0` | **`-0x18`** |
| `__TEXT.__constg_swiftt` | `0x7d10` | `0x7cfc` | **`-0x14`** |
| `__TEXT.__swift5_builtin` | `0x1f4` | `0x1e0` | **`-0x14`** |
| `__DATA_DIRTY.__objc_data` | `0x2f0` | `0x2e0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x1844` | `0x1834` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x1138` | `0x1144` | **`+0xc`** |
| `__AUTH.__objc_data` | `0x3a20` | `0x3a28` | **`+0x8`** |
| `__AUTH_CONST.__auth_got` | `0x46f0` | `0x46f8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ac0` | `0x1ab8` | **`-0x8`** |
| `__DATA_DIRTY.__data` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x728` | `0x730` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x60c` | `0x608` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x67c` | `0x680` | **`+0x4`** |

### Other Changes

```diff

-9.107.1.0.0
+9.108.0.0.0

-  Functions: 10301
-  Symbols:   3698
-  CStrings:  1869
+  Functions: 10340
+  Symbols:   3704
+  CStrings:  1873
Symbols:
+ _CGRectIsEmpty
+ _UIInterfaceOrientationIsPortrait
+ ___swift_closure_destructor.62Tm
+ ___swift_memcpy120_8
+ ___swift_memcpy12_4
+ _get_enum_tag_for_layout_string 7SwiftUI11EnvironmentV7ContentOy9CoreIDVUI32IdentityProofingNFCScanViewModelC_G
+ _symbolic _____ 9CoreIDVUI17PassportSceneViewC16V68OpenPlacementV
+ _symbolic _____Sg 9CoreIDVUI17PassportSceneViewC16V68OpenPlacementV
+ _symbolic _____y_____G 7SwiftUI8BindableV 9CoreIDVUI32IdentityProofingNFCScanViewModelC
+ _type_layout_string 9CoreIDVUI17PassportSceneViewC16V68OpenPlacementV
+ _type_layout_string 9CoreIDVUI27IdentityProofingNFCScanViewV
- ___swift_closure_destructor.59Tm
- ___swift_memcpy152_8
- _symbolic _____ So26CGImagePropertyOrientationV
- _symbolic _____y_____G 2os21OSAllocatedUnfairLockV So26CGImagePropertyOrientationV
- _symbolic _____y__________G s13ManagedBufferCsRi__rlE So26CGImagePropertyOrientationV So16os_unfair_lock_sV
CStrings:
+ "NFCScanViewConfig not restarting NFC session while the rotate correction is shown"
+ "NFCScanViewConfig not starting NFC session while the rotate correction is shown"
+ "NFCScanViewConfig rotate correction appeared while starting; ending NFC session"
+ "NFCScanViewConfig rotate correction cleared; resuming NFC from state %{public}s"
+ "NFCScanViewConfig rotate correction shown; pausing NFC in state %{public}s"
- "IDScanCameraReader: buffer orientation changed %{public}u -> %{public}u"
```

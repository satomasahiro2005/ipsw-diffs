## CommunicationsUICore

> `/System/Library/PrivateFrameworks/CommunicationsUICore.framework/CommunicationsUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdcda4` | `0xde748` | **`+0x19a4`** |
| `__AUTH_CONST.__objc_const` | `0x14578` | `0x14748` | **`+0x1d0`** |
| `__TEXT.__swift5_typeref` | `0x3e86` | `0x3f62` | **`+0xdc`** |
| `__TEXT.__const` | `0x7eb4` | `0x7f54` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x5280` | `0x5308` | **`+0x88`** |
| `__DATA.__data` | `0x2028` | `0x2098` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x27a4` | `0x2808` | **`+0x64`** |
| `__TEXT.__oslogstring` | `0x4e81` | `0x4e21` | **`-0x60`** |
| `__TEXT.__cstring` | `0x2081` | `0x20d1` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x2625` | `0x2675` | **`+0x50`** |
| `__DATA_DIRTY.__data` | `0x26e8` | `0x2718` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1534` | `0x155c` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2d50` | `0x2d78` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1488` | `0x14a8` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x306c` | `0x3088` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0xa20` | `0xa30` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1548` | `0x1558` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xff8` | `0xffc` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x2a4` | `0x2a8` | **`+0x4`** |

### Other Changes

```diff

-139.100.27.2.9
+143.100.11.2.1

-  Functions: 4309
-  Symbols:   1728
-  CStrings:  559
+  Functions: 4329
+  Symbols:   1739
+  CStrings:  560
Symbols:
+ ___swift_memcpy25_8
+ _clock_gettime_nsec_np
+ _symbolic _____ 20CommunicationsUICore13SecondaryViewV
+ _symbolic _____17presentationStyle______Sgyc13evaluatedViewtSg 20CommunicationsUICore10FTMenuItemC30SecondaryViewPresentationStyleO AA0eF0V
+ _symbolic _____Sg s6UInt64V
+ _symbolic _____SgXw 20CommunicationsUICore19CameraZoomViewModelC
+ _symbolic _____Sgz_Xx s6UInt64V
+ _symbolic ______pSgSdSgIeggy_ s5ErrorP
+ _symbolic _____y______ySb_____GG 7Combine10PublishersO6FilterV AA12AnyPublisherV s5NeverO
+ _symbolic _____y______y__________GSbG 7Combine10PublishersO3MapV AA19CurrentValueSubjectC 20CommunicationsUICore11RemoteVideoO15ConnectionStateO s5NeverO
+ _symbolic _____y______y______ySb_____GGytG 7Combine10PublishersO3MapV AC6FilterV AA12AnyPublisherV s5NeverO
+ _symbolic _____y______y______y__________GSbGG 7Combine10PublishersO16RemoveDuplicatesV AC3MapV AA19CurrentValueSubjectC 20CommunicationsUICore11RemoteVideoO15ConnectionStateO s5NeverO
+ _symbolic _____y______y______y______ySb_____GGytGADyytAEGG 7Combine10PublishersO5MergeV AC3MapV AC6FilterV AA12AnyPublisherV s5NeverO
+ _symbolic _____y______y______y______y______ySb_____GGytGAEyytAFGGSo9NSRunLoopCG 7Combine10PublishersO9ReceiveOnV AC5MergeV AC3MapV AC6FilterV AA12AnyPublisherV s5NeverO
+ _type_layout_string 20CommunicationsUICore13SecondaryViewV
- _symbolic SS5title______4viewtSgIego_ 7SwiftUI7AnyViewV
- _symbolic SS5title______4viewtSgIegr_ 7SwiftUI7AnyViewV
- _symbolic SiIegy_
- _symbolic _____17presentationStyle_SS5title______4viewtSgyc13evaluatedViewtSg 20CommunicationsUICore10FTMenuItemC30SecondaryViewPresentationStyleO 7SwiftUI03AnyF0V
CStrings:
+ "Dual camera mode enabled, waiting for secondary stream first frame"
+ "MIC_MODES_ROW_TITLE"
+ "Restoring secondary camera zoom factor: %f"
+ "Secondary stream first frame received"
+ "SecondaryCameraFirstFrameTimeoutSeconds"
- "Dual camera mode enabled after secondary stream connected"
- "Dual camera mode requested, waiting for secondary stream connection"
- "Estimated duration: %f"
- "Transitioning to dual mode (connection is .connected and displayMode is .single)"
```

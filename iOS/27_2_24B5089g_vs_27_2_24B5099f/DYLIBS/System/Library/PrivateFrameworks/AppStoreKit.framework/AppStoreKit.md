## AppStoreKit

> `/System/Library/PrivateFrameworks/AppStoreKit.framework/AppStoreKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x862eac` | `0x86849c` | **`+0x55f0`** |
| `__TEXT.__eh_frame` | `0x1f3d0` | `0x1f6ac` | **`+0x2dc`** |
| `__AUTH_CONST.__const` | `0x4d7a8` | `0x4d9f8` | **`+0x250`** |
| `__AUTH.__data` | `0x11b88` | `0x11d58` | **`+0x1d0`** |
| `__AUTH_CONST.__objc_const` | `0x48f98` | `0x49140` | **`+0x1a8`** |
| `__TEXT.__const` | `0x5ef54` | `0x5f0e4` | **`+0x190`** |
| `__TEXT.__unwind_info` | `0x1c8d0` | `0x1ca28` | **`+0x158`** |
| `__TEXT.__cstring` | `0x2236d` | `0x2248d` | **`+0x120`** |
| `__TEXT.__swift5_capture` | `0xc874` | `0xc97c` | **`+0x108`** |
| `__TEXT.__constg_swiftt` | `0x2191c` | `0x219e8` | **`+0xcc`** |
| `__TEXT.__swift5_typeref` | `0x1c214` | `0x1c2d6` | **`+0xc2`** |
| `__TEXT.__swift5_fieldmd` | `0x1ff38` | `0x1ffd4` | **`+0x9c`** |
| `__DATA_DIRTY.__data` | `0x2ef58` | `0x2efe0` | **`+0x88`** |
| `__AUTH_CONST.__auth_got` | `0x55c0` | `0x5640` | **`+0x80`** |
| `__DATA.__bss` | `0x39ef0` | `0x39f70` | **`+0x80`** |
| `__DATA.__data` | `0xbf08` | `0xbf78` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x22ab0` | `0x22b20` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x4530` | `0x4580` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x2ba0` | `0x2bd8` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x4c10` | `0x4bf8` | **`-0x18`** |
| `__TEXT.__swift_as_cont` | `0x9dc` | `0x9f0` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x4bb8` | `0x4bc8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1468` | `0x1478` | **`+0x10`** |
| `__DATA_DIRTY.__objc_data` | `0x96c8` | `0x96d8` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x1d6c` | `0x1d78` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x4b4` | `0x4bc` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x504` | `0x50c` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x35f4` | `0x35f8` | **`+0x4`** |

### Other Changes

```diff

-27.1.20.0.0
+27.1.23.2.1

-  Functions: 45936
-  Symbols:   12930
-  CStrings:  3854
+  Functions: 46028
+  Symbols:   12951
+  CStrings:  3860
Symbols:
+ _NSURLErrorDomain
+ __DATA__TtC11AppStoreKit13TaskThrottler
+ __DATA__TtC11AppStoreKit24WindowResizeStateMonitor
+ __IVARS__TtC11AppStoreKit13TaskThrottler
+ __IVARS__TtC11AppStoreKit24WindowResizeStateMonitor
+ __METACLASS_DATA__TtC11AppStoreKit13TaskThrottler
+ __METACLASS_DATA__TtC11AppStoreKit24WindowResizeStateMonitor
+ ___swift_closure_destructor.105Tm
+ ___swift_closure_destructor.111Tm
+ _associated conformance 11AppStoreKit21JSPromiseBindingErrorO10Foundation09LocalizedF0AAs0F0
+ _symbolic SayypGSg
+ _symbolic So9JSContextCSo7JSValueCIeggg_Sg
+ _symbolic _____ 11AppStoreKit13TaskThrottlerC
+ _symbolic _____ 11AppStoreKit13TaskThrottlerC5State33_63DC1FF0E9CC8187047518DF52E23ED9LLV
+ _symbolic _____ 11AppStoreKit24WindowResizeStateMonitorC
+ _symbolic _____ 7SwiftUI14HorizontalEdgeO3SetV
+ _symbolic _____ s15ContinuousClockV
+ _symbolic _____ s8DurationV
+ _symbolic _____Sg 11AppStoreKit24WindowResizeStateMonitorC
+ _symbolic _____Sg s15ContinuousClockV7InstantV
+ _symbolic _____Sg s8DurationV
+ _symbolic _____SgXw 11AppStoreKit13TaskThrottlerC
+ _symbolic _____SgXw 11AppStoreKit26JSInvalidSignatureReporterC
+ _symbolic _____SgXwz_Xx 11AppStoreKit13TaskThrottlerC
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 11AppStoreKit13TaskThrottlerC5State33_63DC1FF0E9CC8187047518DF52E23ED9LLV
+ _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE 11AppStoreKit13TaskThrottlerC5State33_63DC1FF0E9CC8187047518DF52E23ED9LLV
- _OBJC_CLASS_$_CASpringAnimation
- ___swift_closure_destructor.22Tm
- ___swift_closure_destructor.25Tm
- ___swift_closure_destructor.77Tm
- ___swift_closure_destructor.83Tm
CStrings:
+ "0681401B-E3A8-4EBC-99B3-BDCB292AA25D"
+ "B743E555-E2A6-44AA-AE20-8C5BFE608797"
+ "Native promise exceeded its JavaScript timeout"
+ "No current JavaScript worker thread"
+ "SystemAppIcon: Icon Services cache is cold for "
+ "enable-ad-curation-timeout-reporting"
```

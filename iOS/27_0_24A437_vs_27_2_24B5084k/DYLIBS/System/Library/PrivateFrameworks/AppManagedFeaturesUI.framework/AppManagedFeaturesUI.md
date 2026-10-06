## AppManagedFeaturesUI

> `/System/Library/PrivateFrameworks/AppManagedFeaturesUI.framework/AppManagedFeaturesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23914` | `0x24490` | **`+0xb7c`** |
| `__TEXT.__cstring` | `0xc71` | `0xd31` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x1378` | `0x1400` | **`+0x88`** |
| `__AUTH_CONST.__const` | `0xf50` | `0xfc8` | **`+0x78`** |
| `__TEXT.__const` | `0x1258` | `0x12a8` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x9f8` | `0xa48` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x119e` | `0x11d8` | **`+0x3a`** |
| `__AUTH_CONST.__objc_const` | `0x8b8` | `0x8f0` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0xb38` | `0xb68` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x3d8` | `0x3fc` | **`+0x24`** |
| `__AUTH.__objc_data` | `0x838` | `0x858` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x408` | `0x428` | **`+0x20`** |
| `__DATA.__data` | `0x758` | `0x770` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x4a8` | `0x4c0` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x840` | `0x858` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x35c` | `0x374` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xf0` | `0x100` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x8ee` | `0x8fe` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x4f4` | `0x500` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x104` | `0x110` | **`+0xc`** |
| `__DATA.__common` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x68` | `0x6c` | **`+0x4`** |

### Other Changes

```diff

-46.0.15.0.0
+58.40.9.0.0

+  - /System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices

-  Functions: 711
-  Symbols:   529
+  Functions: 730
+  Symbols:   542
Symbols:
+ _FBSOpenApplicationOptionKeyPromptUnlockDevice
+ _FBSOpenApplicationOptionKeyUnlockDevice
+ _OBJC_CLASS_$__LSOpenConfiguration
+ __PROPERTIES__TtC20AppManagedFeaturesUI28EnrollmentControllerProvider
+ ___swift_closure_destructor.12Tm
+ ___swift_closure_destructor.67Tm
+ __swiftEmptyDictionarySingleton
+ _objc_retain_x28
+ _swift_initStackObject
+ _swift_setDeallocating
+ _symbolic SS_ypt
+ _symbolic _____SgXw 20AppManagedFeaturesUI28EnrollmentControllerProviderC
+ _symbolic _____SgXwz_Xx 20AppManagedFeaturesUI28EnrollmentControllerProviderC
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
+ _symbolic _____ySSypG s18_DictionaryStorageC
- ___swift_closure_destructor.29Tm
- ___swift_closure_destructor.66Tm
CStrings:
+ " can require and install software updates that fix critical issues and improve device security. \n\nThis app below can’t be removed while your device is under contract, and it may update automatically even if you’ve turned off automatic app updates in Settings."
+ " can require and install software updates that fix critical issues and improve device security. \n\nThis app below can’t be removed while your device is under contract, and it may update automatically even if you’ve turned off automatic app updates in Settings. You can remove the preferred payment app at any time."
+ "Could not open provider app: %{public}@"
- " may require and install software updates to address critical issues and device security. \n\nThis app below cannot be removed while your device is under contract."
- " may require and install software updates to address critical issues and device security. \n\nThis app below cannot be removed while your device is under contract. You may remove the preferred payment app at any time."
- "Could not open provider app"
```

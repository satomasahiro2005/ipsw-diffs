## SpotlightUIServices

> `/System/Library/PrivateFrameworks/SpotlightUIServices.framework/SpotlightUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x539d4` | `0x53938` | **`-0x9c`** |
| `__TEXT.__cstring` | `0x2540` | `0x25c0` | **`+0x80`** |
| `__DATA_DIRTY.__objc_data` | `0x1c18` | `0x1bb0` | **`-0x68`** |
| `__AUTH_CONST.__cfstring` | `0x2920` | `0x2980` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x860` | `0x818` | **`-0x48`** |
| `__TEXT.__oslogstring` | `0xa1b` | `0xa5b` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x7220` | `0x71e8` | **`-0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e60` | `0x2e98` | **`+0x38`** |
| `__DATA_DIRTY.__data` | `0x2e0` | `0x2b0` | **`-0x30`** |
| `__TEXT.__const` | `0xc24` | `0xbf4` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x6b8` | `0x68c` | **`-0x2c`** |
| `__AUTH_CONST.__auth_got` | `0xb48` | `0xb38` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x5c0` | `0x5d0` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x1e8` | `0x1d8` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x258` | `0x248` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x480` | `0x470` | **`-0x10`** |
| `__DATA.__data` | `0x1e0` | `0x1d8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x2f8` | `0x2f0` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x4d30` | `0x4d38` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1418` | `0x1420` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x58` | `0x54` | **`-0x4`** |

### Other Changes

```diff

-236.0.4.100.0
+236.0.11.100.0

+  - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices

-  Functions: 2175
-  Symbols:   3563
-  CStrings:  458
+  Functions: 2177
+  Symbols:   3557
+  CStrings:  464
Symbols:
+ +[SPUISUtilities shouldSuppressAskSiriForAuthenticationState:]
+ +[SPUISUtilities shouldSuppressAskSiriForAuthenticationState:assistantDisabledWhileLocked:]
+ +[SPUISUtilities syntheticCollapsedShowMoreResult]
+ _OBJC_CLASS_$_AFPreferences
- _OBJC_CLASS_$_SFResultSection
- _OBJC_CLASS_$_SPUISSearchResultUtilities
- _OBJC_METACLASS_$_SPUISSearchResultUtilities
- __CLASS_METHODS_SPUISSearchResultUtilities
- __DATA_SPUISSearchResultUtilities
- __INSTANCE_METHODS_SPUISSearchResultUtilities
- __METACLASS_DATA_SPUISSearchResultUtilities
- _swift_initStackObject
- _symbolic _____ 19SpotlightUIServices21SearchResultUtilitiesC
- _symbolic _____ySSG s11_SetStorageC
CStrings:
+ "TopHitExpandDelay"
+ "TopHitExpandDelayEnabled"
+ "biometryLockout"
+ "com.apple.collapsedShowMore"
+ "isSiriDisabledWhileLocked: %@ authenticationState: %@"
+ "passcodeLocked"
+ "unlocked"
- "com.apple.Campo"
```

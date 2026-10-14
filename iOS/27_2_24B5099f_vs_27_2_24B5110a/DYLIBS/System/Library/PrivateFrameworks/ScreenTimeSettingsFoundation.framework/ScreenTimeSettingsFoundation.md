## ScreenTimeSettingsFoundation

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsFoundation.framework/ScreenTimeSettingsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20adec` | `0x21047c` | **`+0x5690`** |
| `__TEXT.__oslogstring` | `0xb0a2` | `0xb422` | **`+0x380`** |
| `__TEXT.__eh_frame` | `0x9280` | `0x92f4` | **`+0x74`** |
| `__AUTH_CONST.__auth_got` | `0x3230` | `0x3290` | **`+0x60`** |
| `__DATA_DIRTY.__data` | `0x35e0` | `0x3630` | **`+0x50`** |
| `__TEXT.__const` | `0x8020` | `0x8050` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x26c8` | `0x26f8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x3668` | `0x3698` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x8208` | `0x8230` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x80` | `0xa0` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x25d8` | `0x25f0` | **`+0x18`** |
| `__DATA.__data` | `0x13c8` | `0x13d8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x328` | `0x338` | **`+0x10`** |
| `__TEXT.__cstring` | `0x2b53` | `0x2b63` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x15b4` | `0x15c4` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xf50` | `0xf58` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x553a` | `0x5542` | **`+0x8`** |

### Other Changes

```diff

-97.1.12.0.0
+97.1.14.0.0

+  - /System/Library/Frameworks/UIKit.framework/UIKit

+  - /System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices

+  - /usr/lib/swift/libswiftSpatial.dylib

-  Functions: 4394
-  Symbols:   1949
-  CStrings:  909
+  Functions: 4405
+  Symbols:   1955
+  CStrings:  924
Symbols:
+ _SBSCopyDisplayIdentifiers
+ ___swift_closure_destructor.134Tm
+ ___swift_closure_destructor.168Tm
+ ___swift_closure_destructor.176Tm
+ ___swift_closure_destructor.41Tm
+ ___swift_closure_destructor.45Tm
+ ___swift_closure_destructor.52Tm
+ ___swift_closure_destructor.57Tm
+ ___swift_closure_destructor.61Tm
+ ___swift_closure_destructor.76Tm
+ ___swift_closure_destructor.99Tm
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftSpatial_$_ScreenTimeSettingsFoundation
+ __swift_FORCE_LOAD_$_swiftUIKit
+ __swift_FORCE_LOAD_$_swiftUIKit_$_ScreenTimeSettingsFoundation
+ _swift_getFunctionTypeMetadata0
+ _symbolic _____Sg 26ScreenTimeSettingsServices0abC0C28RegulatoryComplianceStrategyO
- ___swift_closure_destructor.100Tm
- ___swift_closure_destructor.135Tm
- ___swift_closure_destructor.169Tm
- ___swift_closure_destructor.177Tm
- ___swift_closure_destructor.43Tm
- ___swift_closure_destructor.47Tm
- ___swift_closure_destructor.54Tm
- ___swift_closure_destructor.59Tm
- ___swift_closure_destructor.63Tm
- ___swift_closure_destructor.78Tm
- ___swift_memcpy33_8
CStrings:
+ "DeviceClass"
+ "Failed to reconcile allowed web domains: %{public}s"
+ "Failed to reconcile always-allowed apps: %{public}s"
+ "Failed to reconcile app exceptions: %{public}s"
+ "Failed to reconcile blocked web domains: %{public}s"
+ "Failed to reconcile bundled time allowance groups: %{public}s"
+ "Failed to reconcile installed apps: %{public}s"
+ "Failed to reconcile one-more-minute exceptions: %{public}s"
+ "Failed to reconcile passcode activity log: %{public}s"
+ "Failed to reconcile restricted apps: %{public}s"
+ "Failed to reconcile time allowance exceptions: %{public}s"
+ "Failed to reconcile time allowance group entries: %{public}s"
+ "Failed to reconcile time allowance groups: %{public}s"
+ "Saving update for %{public}s [%{private}s] even though it is not compliant with the regulatory policy"
+ "SpringBoard returned no launchable display identifiers"
```

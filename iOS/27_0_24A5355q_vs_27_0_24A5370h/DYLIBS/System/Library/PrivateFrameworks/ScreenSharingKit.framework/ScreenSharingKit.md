## ScreenSharingKit

> `/System/Library/PrivateFrameworks/ScreenSharingKit.framework/ScreenSharingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25ec30` | `0x2615ec` | **`+0x29bc`** |
| `__TEXT.__eh_frame` | `0x17f40` | `0x18138` | **`+0x1f8`** |
| `__TEXT.__cstring` | `0x8f55` | `0x9145` | **`+0x1f0`** |
| `__TEXT.__swift5_mpenum` | `0x1a0` | `0xc8` | **`-0xd8`** |
| `__TEXT.__const` | `0x19724` | `0x19654` | **`-0xd0`** |
| `__AUTH_CONST.__const` | `0x109f0` | `0x10a90` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x3c9c` | `0x3d30` | **`+0x94`** |
| `__TEXT.__oslogstring` | `0xb955` | `0xb9c5` | **`+0x70`** |
| `__TEXT.__swift_as_cont` | `0x18c8` | `0x1910` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x8e50` | `0x8e78` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x8e95` | `0x8eb5` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x794c` | `0x7932` | **`-0x1a`** |
| `__DATA.__data` | `0x57e8` | `0x57f8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x70f4` | `0x7100` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0xa64` | `0xa70` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1838` | `0x1840` | **`+0x8`** |
| `__DATA.__bss` | `0x1d778` | `0x1d780` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x9cc` | `0x9d4` | **`+0x8`** |

### Other Changes

```diff

-114.38.11.1.0
+114.44.0.0.0

-  Functions: 9642
-  Symbols:   3412
-  CStrings:  1541
+  Functions: 9655
+  Symbols:   3410
+  CStrings:  1552
Symbols:
+ ___swift_closure_destructor.113Tm
+ ___swift_closure_destructor.119Tm
+ ___swift_closure_destructor.132Tm
+ ___swift_closure_destructor.14Tm
+ ___swift_closure_destructor.162Tm
+ ___swift_closure_destructor.241Tm
+ _swift_deallocUninitializedObject
- ___swift_closure_destructor.109Tm
- ___swift_closure_destructor.115Tm
- ___swift_closure_destructor.131Tm
- ___swift_closure_destructor.13Tm
- ___swift_closure_destructor.161Tm
- ___swift_closure_destructor.238Tm
- _symbolic _____Sg 16ScreenSharingKit17ClientStatusEventO
- _symbolic _____Xo 16ScreenSharingKit14PlaybackServerC
- _symbolic ______AAt 16ScreenSharingKit17ClientStatusEventO
CStrings:
+ "Activated RemoteDisplaySession"
+ "Activating MCKBackedContinuityClientSession"
+ "Activating RemoteDisplaySession"
+ "Cancelled monitoring tasks"
+ "ContinuitySession activation failed with error"
+ "Invalidating MCKBackedContinuityClientSession while awaiting activation"
+ "Invalidating RemoteDisplaySession while awaiting activation"
+ "Received clientStartupConfiguration with config: %{public}s"
+ "Received launchPayload of type: %{public}s and data size: %{public}ld bytes"
+ "SSKBringupSessionInitializing"
+ "SceneInteractorBackedContinuitySession deinitialized with %ld outstanding monitoring tasks"
+ "client startup config contains system gesture event: %{public}s"
- "Session terminated before activation could complete, bailing out"
```

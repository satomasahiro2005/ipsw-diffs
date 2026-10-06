## AppManagedFeaturesUI

> `/Applications/LimitedModeShieldApp.app/Frameworks/AppManagedFeaturesUI.framework/AppManagedFeaturesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x224c4` | `0x23450` | **`+0xf8c`** |
| `__TEXT.__eh_frame` | `0x12a0` | `0x1378` | **`+0xd8`** |
| `__AUTH_CONST.__const` | `0xe88` | `0xf50` | **`+0xc8`** |
| `__TEXT.__auth_stubs` | `0x15d0` | `0x1640` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x87e` | `0x8ee` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x390` | `0x3d8` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x9b8` | `0x9f8` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0xaf0` | `0xb28` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x11d2` | `0x119e` | **`-0x34`** |
| `__TEXT.__cstring` | `0xb81` | `0xbb1` | **`+0x30`** |
| `__TEXT.__const` | `0x1218` | `0x1238` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x2b7` | `0x2d7` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xda0` | `0xd80` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x3b8` | `0x3c8` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xf8` | `0x104` | **`+0xc`** |
| `__DATA.__data` | `0x740` | `0x748` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4b0` | `0x4a8` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x64` | `0x68` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x68` | `0x6c` | **`+0x4`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH.__objc_data`
- `__AUTH_CONST.__objc_const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-46.0.5.0.0
+46.0.7.0.0

-  Functions: 689
-  Symbols:   636
-  CStrings:  324
+  Functions: 707
+  Symbols:   640
+  CStrings:  327
Symbols:
+ ___swift_allocate_boxed_opaque_existential_0
+ ___swift_project_boxed_opaque_existential_0
+ __swift_closure_destructor.29Tm
+ _objc_msgSend$createConnectionWithCompletionBlock:
+ _swift_allocBox
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_willThrow
+ _symbolic Ieg_
+ _symbolic ScCyyt______pG s5ErrorP
+ _symbolic ytIegr_
- _OBJC_CLASS_$_UINavigationController
- __swift_closure_destructor.21Tm
- _objc_msgSend$initWithRootViewController:
- _objc_msgSend$setModalPresentationStyle:
- _symbolic So16UIViewControllerCIego_
- _symbolic So16UIViewControllerCIegr_
- _symbolic So16UIViewControllerCycSg
CStrings:
+ "Failed to pre-warm ASCLockupView connection: %{public}s"
+ "Failed to read management provider: %{public}s"
+ "_createCheckedThrowingContinuation(_:)"
+ "createConnectionWithCompletionBlock:"
+ "v16@?0@\"NSError\"8"
- "initWithRootViewController:"
- "setModalPresentationStyle:"
```

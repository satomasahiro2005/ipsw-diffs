## PrivacyAccounting

> `/System/Library/PrivateFrameworks/PrivacyAccounting.framework/PrivacyAccounting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c6b8` | `0x1d5dc` | **`+0xf24`** |
| `__AUTH_CONST.__auth_got` | `0x760` | `0x7f0` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x9dc` | `0xa3f` | **`+0x63`** |
| `__TEXT.__cstring` | `0x10fc` | `0x113c` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xaa0` | `0xad0` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x600` | `0x628` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x308` | `0x330` | **`+0x28`** |
| `__TEXT.__const` | `0x690` | `0x6b0` | **`+0x20`** |
| `__DATA.__common` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x1fd` | `0x213` | **`+0x16`** |
| `__DATA.__data` | `0xa50` | `0xa60` | **`+0x10`** |
| `__DATA_DIRTY.__common` | `0x8` | `—` | **`-0x8`** |
| `__DATA_DIRTY.__data` | `0x30` | `0x28` | **`-0x8`** |

### Other Changes

```diff

-149.0.0.0.0
+150.0.0.0.0

+  - /System/Library/PrivateFrameworks/OSEligibility.framework/OSEligibility

-  Functions: 873
-  Symbols:   1738
-  CStrings:  206
+  Functions: 884
+  Symbols:   1747
+  CStrings:  210
Symbols:
+ ___swift_allocate_value_buffer
+ ___swift_destroy_boxed_opaque_existential_0
+ ___swift_project_value_buffer
+ __swiftImmortalRefCount
+ _swift_arrayDestroy
+ _swift_errorRetain
+ _swift_getObjectType
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _symbolic ______p s5ErrorP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
- _MobileGestalt_get_current_device
- _MobileGestalt_get_greenTeaDeviceCapability
CStrings:
+ "Failed to read eligibility for %{public}s: %{public}s"
+ "OSEligibility result%{public}s"
+ "OSEligibilityClient"
+ "com.apple.privacyaccounting"
```

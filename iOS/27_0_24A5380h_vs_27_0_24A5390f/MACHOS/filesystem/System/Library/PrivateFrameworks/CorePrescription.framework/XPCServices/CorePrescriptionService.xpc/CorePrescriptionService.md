## CorePrescriptionService

> `/System/Library/PrivateFrameworks/CorePrescription.framework/XPCServices/CorePrescriptionService.xpc/CorePrescriptionService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd256c` | `0xd5298` | **`+0x2d2c`** |
| `__TEXT.__eh_frame` | `0xa580` | `0xa8f0` | **`+0x370`** |
| `__TEXT.__cstring` | `0x41ac` | `0x432c` | **`+0x180`** |
| `__TEXT.__auth_stubs` | `0x1fb0` | `0x2060` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x44d8` | `0x4588` | **`+0xb0`** |
| `__TEXT.__const` | `0xd15c` | `0xd1fc` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x52a0` | `0x5318` | **`+0x78`** |
| `__TEXT.__objc_methname` | `0x5067` | `0x50c7` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0xfe0` | `0x1038` | **`+0x58`** |
| `__DATA.__objc_const` | `0x6e28` | `0x6e70` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x1824` | `0x1864` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x22b3` | `0x22f3` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x9f4` | `0xa30` | **`+0x3c`** |
| `__TEXT.__swift_as_ret` | `0x464` | `0x488` | **`+0x24`** |
| `__DATA.__data` | `0x4470` | `0x4490` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x5d8` | `0x5f8` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x201c` | `0x2034` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x3d4` | `0x3ec` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x213c` | `0x2150` | **`+0x14`** |
| `__TEXT.__swift5_typeref` | `0x16a2` | `0x16b4` | **`+0x12`** |
| `__TEXT.__objc_methtype` | `0x17dd` | `0x17cd` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0xd12` | `0xd22` | **`+0x10`** |
| `__DATA.__objc_data` | `0x2800` | `0x2808` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xf18` | `0xf20` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x948` | `0x950` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x2cf8` | `0x2d00` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-230.0.2.0.0
+230.0.3.0.0

-  Functions: 4266
+  Functions: 4311

-  CStrings:  1595
+  CStrings:  1611
CStrings:
+ "%s error: %@"
+ "%s setting: %s"
+ "_preferredLanguages"
+ "lensPoseFailedOnUserPresence"
+ "lensSelectionUpdateAction"
+ "lensSelectionUpdateRXUUID"
+ "preferredLanguages"
+ "prescriptionPresenceRequired"
+ "previousEnrollmentGroup"
+ "requireLensPoseOnUserPresence"
+ "requireLensPoseProcessing"
+ "requirePreUnlockProcessing"
+ "requireProcessingOnUserPresence"
+ "setPreferredLanguages(_:)"
+ "setPreferredLanguages:completionHandler:"
+ "userPresenceDetected"
```

## CorePrescriptionService

> `/System/Library/PrivateFrameworks/CorePrescription.framework/XPCServices/CorePrescriptionService.xpc/CorePrescriptionService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd5298` | `0xd542c` | **`+0x194`** |
| `__TEXT.__cstring` | `0x432c` | `0x420c` | **`-0x120`** |
| `__TEXT.__objc_methname` | `0x50c7` | `0x5017` | **`-0xb0`** |
| `__TEXT.__oslogstring` | `0xd22` | `0xdc2` | **`+0xa0`** |
| `__DATA.__data` | `0x4490` | `0x4520` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x22f3` | `0x2263` | **`-0x90`** |
| `__TEXT.__constg_swiftt` | `0x2d00` | `0x2d4c` | **`+0x4c`** |
| `__TEXT.__auth_stubs` | `0x2060` | `0x2020` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0xa8f0` | `0xa930` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0xee2` | `0xf22` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x16e0` | `0x16a0` | **`-0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x2034` | `0x2008` | **`-0x2c`** |
| `__TEXT.__unwind_info` | `0x4588` | `0x45b0` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x1038` | `0x1018` | **`-0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x950` | `0x938` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0x16b4` | `0x16c6` | **`+0x12`** |
| `__DATA.__objc_selrefs` | `0xf20` | `0xf10` | **`-0x10`** |
| `__TEXT.__const` | `0xd1fc` | `0xd20c` | **`+0x10`** |
| `__DATA.__common` | `0x238` | `0x244` | **`+0xc`** |
| `__DATA.__objc_const` | `0x6e70` | `0x6e68` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x5f8` | `0x600` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x240` | `0x248` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x220` | `0x224` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-230.0.3.0.0
+230.0.5.0.0

-  Functions: 4311
-  Symbols:   520
-  CStrings:  1611
+  Functions: 4319
+  Symbols:   523
+  CStrings:  1598
Symbols:
+ _CFBundleCopyLocalizedStringForLocalizations
+ _CFBundleGetMainBundle
+ _OBJC_CLASS_$_NSLock
CStrings:
+ "_TtC23CorePrescriptionService22PreferredLanguageStore"
+ "languages"
+ "lock"
+ "prepareDatabase: no persisted preferredLanguages; localization falls back to ambient"
+ "prepareDatabase: reloaded persisted preferredLanguages: %s"
+ "unlock"
- "Guest Optical Inserts"
- "PRESCRIPTION_NAME_DEFAULT"
- "PRESCRIPTION_NAME_DEMO_LENSES"
- "PRESCRIPTION_NAME_DEVELOPER_LENSES"
- "PRESCRIPTION_NAME_GUEST_LENSES"
- "PRESCRIPTION_NAME_PRESCRIPTION_LENSES"
- "PRESCRIPTION_NAME_READER_LENSES"
- "Prescription Inserts"
- "URLForResource:withExtension:"
- "_preferredLanguages"
- "defaultLensName"
- "demoLensName"
- "developerLensName"
- "guestLensName"
- "initWithURL:"
- "localizations"
- "preferredLocalizationsFromArray:forPreferences:"
- "prescriptionLensName"
- "readerLensName"
```

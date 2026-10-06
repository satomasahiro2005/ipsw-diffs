## BackgroundSecurityImprovement

> `/System/Library/PreferenceBundles/BackgroundSecurityImprovement.bundle/BackgroundSecurityImprovement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd96b0` | `0xd7abc` | **`-0x1bf4`** |
| `__TEXT.__swift5_typeref` | `0x49e4` | `0x45de` | **`-0x406`** |
| `__TEXT.__oslogstring` | `0x297a` | `0x29fa` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x6950` | `0x69c0` | **`+0x70`** |
| `__TEXT.__cstring` | `0x1c0c` | `0x1c7c` | **`+0x70`** |
| `__DATA.__common` | `0x60` | `0xa8` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x1f14` | `0x1f3c` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2470` | `0x2498` | **`+0x28`** |
| `__DATA.__bss` | `0x1168` | `0x1188` | **`+0x20`** |
| `__TEXT.__const` | `0x29f8` | `0x2a18` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x298c` | `0x29ac` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x9f4` | `0x9d4` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0xa68` | `0xa84` | **`+0x1c`** |
| `__DATA_CONST.__auth_ptr` | `0x518` | `0x520` | **`+0x8`** |
| `__TEXT.__swift5_fieldmd` | `0x5c8` | `0x5cc` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xac` | `0xb0` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x158` | `0x154` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-772.0.0.0.0
+772.0.3.0.0

-  Functions: 3518
+  Functions: 3522

-  CStrings:  592
+  CStrings:  597
CStrings:
+ "Background Security Improvements"
+ "BackgroundSecurityImprovement/BSIConstants.swift"
+ "Found installFinishedBootUUID: %s, current: %s"
+ "Found rollbackFinishedBootUUID: %s, current: %s"
+ "Unable to get boot UUID"
+ "com.apple.Preferences"
- "Background Security Updates"
```

## MobileSlideShowSettings

> `/System/Library/PreferenceBundles/MobileSlideShowSettings.bundle/MobileSlideShowSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1caf8` | `0x1cdac` | **`+0x2b4`** |
| `__DATA_CONST.__cfstring` | `0x2ec0` | `0x2fa0` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x352d` | `0x35df` | **`+0xb2`** |
| `__TEXT.__objc_methname` | `0x49ac` | `0x4a5c` | **`+0xb0`** |
| `__TEXT.__auth_stubs` | `0xe00` | `0xe40` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1438` | `0x1468` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x14b0` | `0x14d8` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x710` | `0x730` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x41e0` | `0x4200` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x758` | `0x770` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x748` | `0x758` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-912.0.234.0.0
+912.0.235.0.0

-  Functions: 505
-  Symbols:   447
-  CStrings:  1375
+  Functions: 509
+  Symbols:   451
+  CStrings:  1387
Symbols:
+ _PLSetShouldExcludeProvenanceOverPTPTransfer
+ _PLSetShouldExcludeProvenanceWhenSharing
+ _PLShouldExcludeProvenanceOverPTPTransfer
+ _PLShouldExcludeProvenanceWhenSharing
CStrings:
+ "PhotosSettingsProvenance"
+ "SHARE_PROVENANCE_FOOTER"
+ "SHARE_PROVENANCE_SETTING"
+ "TRANSFER_PROVENANCE_FOOTER"
+ "TRANSFER_PROVENANCE_SETTING"
+ "TransferProvenanceGroup"
+ "TransferProvenanceSwitch"
+ "provenanceEnabledForSpecifier:"
+ "setProvenanceEnabled:forSpecifier:"
+ "setTarget:"
+ "shouldIncludeProvenanceImageByDefault:"
+ "shouldIncludeProvenanceImageByDefaultWasToggled:specifier:"
```

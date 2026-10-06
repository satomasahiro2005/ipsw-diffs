## Siri

> `/System/Library/DataClassMigrators/Siri.migrator/Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c1c` | `0x3d14` | **`+0xf8`** |
| `__DATA_CONST.__cfstring` | `0x600` | `0x640` | **`+0x40`** |
| `__TEXT.__cstring` | `0x861` | `0x894` | **`+0x33`** |
| `__TEXT.__objc_methname` | `0x940` | `0x963` | **`+0x23`** |
| `__TEXT.__oslogstring` | `0x966` | `0x987` | **`+0x21`** |
| `__TEXT.__objc_stubs` | `0xb60` | `0xb80` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x460` | `0x450` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x1a8` | `0x1b4` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x300` | `0x308` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x238` | `0x230` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.68.45.0.0
+3600.68.61.11.1

-  Functions: 37
-  Symbols:   120
-  CStrings:  222
+  Functions: 38
+  Symbols:   119
+  CStrings:  225
Symbols:
+ _objc_retain_x25
- _objc_release_x26
- _objc_release_x27
Functions:
~ sub_3aa8 : 1936 -> 2076
+ sub_43d4
CStrings:
+ "%s Failed to set TCC denial for bundle %@. [sources: LFTA=%@, ShowContent=%@, ShowApp=%@, Locked=%@]"
+ "%s Marked %@ as denied in kTCCServiceSiriAccess. [sources: LFTA=%@, ShowContent=%@, ShowApp=%@, Locked=%@]"
+ "%s Source counts — LFTA-off: %lu, Show-Content-off: %lu, Show-App-off: %lu, Locked: %lu, Hidden (excluded): %lu, union to migrate: %lu."
+ "SiriCanLearnFromAppBlacklist"
+ "_bundleIdsWithLearnFromAppDisabled"
+ "com.apple.suggestions"
- "%s Failed to set TCC denial for bundle %@. [sources: ShowContent=%@, ShowApp=%@, Locked=%@]"
- "%s Marked %@ as denied in kTCCServiceSiriAccess. [sources: ShowContent=%@, ShowApp=%@, Locked=%@]"
- "%s Source counts — Show-Content-off: %lu, Show-App-off: %lu, Locked: %lu, Hidden (excluded): %lu, union to migrate: %lu."
```

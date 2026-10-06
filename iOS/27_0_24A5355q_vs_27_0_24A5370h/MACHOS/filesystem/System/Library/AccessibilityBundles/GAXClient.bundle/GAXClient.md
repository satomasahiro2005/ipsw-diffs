## GAXClient

> `/System/Library/AccessibilityBundles/GAXClient.bundle/GAXClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0xc18` | `0xc98` | **`+0x80`** |
| `__TEXT.__text` | `0x9d64` | `0x9dd8` | **`+0x74`** |
| `__DATA_CONST.__cfstring` | `0x2940` | `0x2960` | **`+0x20`** |
| `__TEXT.__cstring` | `0x29ad` | `0x29c0` | **`+0x13`** |
| `__TEXT.__auth_stubs` | `0x600` | `0x5f0` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x956` | `0x961` | **`+0xb`** |
| `__DATA_CONST.__auth_got` | `0x310` | `0x308` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x388` | `0x390` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1054.0.0.0.0
+1057.0.0.0.0

-  Functions: 249
+  Functions: 251

-  CStrings:  745
+  CStrings:  746
Symbols:
+ _GAXUIMessageKeyDisplayIdentifier
- _objc_retain_x23
CStrings:
+ "Re-adopted active ASAM session on client load: %@"
+ "display identifier"
- "GAX is active. fetching configuration."
```

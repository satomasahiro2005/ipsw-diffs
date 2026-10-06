## coreauthd

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/coreauthd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38468` | `0x38600` | **`+0x198`** |
| `__TEXT.__const` | `0x1468` | `0x14b8` | **`+0x50`** |
| `__DATA.__data` | `0x1b68` | `0x1b90` | **`+0x28`** |
| `__TEXT.__cstring` | `0x506e` | `0x508c` | **`+0x1e`** |
| `__TEXT.__unwind_info` | `0xd28` | `0xd30` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2319.0.33.0.1
+2319.0.46.0.0

-  Functions: 1561
+  Functions: 1564

-  CStrings:  1838
+  CStrings:  1839
CStrings:
+ "aks_get_convenience_bio_state"
```

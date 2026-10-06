## libCoreKE.dylib

> `/usr/lib/libCoreKE.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16992dc` | `0x15a5e7c` | **`-0xf3460`** |
| `__TEXT.__const` | `0xdd7ec` | `0xdf004` | **`+0x1818`** |
| `__DATA_CONST.__const` | `0x1cbf8` | `0x1d678` | **`+0xa80`** |
| `__TEXT.__cstring` | `0x25f2` | `0x25ca` | **`-0x28`** |
| `__DATA.__data` | `0x5350` | `0x5348` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xc08` | `0xc10` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-  Functions: 822
+  Functions: 820

-  CStrings:  377
+  CStrings:  375
CStrings:
- "aks_fv_new_sibling_vek"
- "aks_stash_escrow"
```

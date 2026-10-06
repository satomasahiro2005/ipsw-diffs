## usermanagerd

> `/usr/libexec/usermanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xae2a0` | `0xae438` | **`+0x198`** |
| `__TEXT.__const` | `0x14a4` | `0x14fc` | **`+0x58`** |
| `__DATA.__data` | `0x12f0` | `0x1318` | **`+0x28`** |
| `__TEXT.__cstring` | `0x76b9` | `0x76d7` | **`+0x1e`** |
| `__TEXT.__unwind_info` | `0x1568` | `0x1570` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 2406
+  Functions: 2409

-  CStrings:  3391
+  CStrings:  3392
CStrings:
+ "aks_get_convenience_bio_state"
```

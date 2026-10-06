## tailspind

> `/usr/libexec/tailspind`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xef98` | `0xeed4` | **`-0xc4`** |
| `__TEXT.__oslogstring` | `0x2bdd` | `0x2b90` | **`-0x4d`** |
| `__TEXT.__cstring` | `0x139c` | `0x1390` | **`-0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 294
+  Functions: 293

-  CStrings:  528
+  CStrings:  526
CStrings:
- "client %s [%d] requested for tailspin data but was rejected by the allowlist"
- "hangtracerd"
```

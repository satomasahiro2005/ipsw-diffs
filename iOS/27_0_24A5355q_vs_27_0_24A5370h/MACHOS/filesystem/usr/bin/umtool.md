## umtool

> `/usr/bin/umtool`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15600` | `0x154d0` | **`-0x130`** |
| `__TEXT.__cstring` | `0x2a3f` | `0x29d8` | **`-0x67`** |
| `__TEXT.__unwind_info` | `0x3e8` | `0x3f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-488.0.0.0.0
+490.0.0.0.0

-  Functions: 501
+  Functions: 497

-  CStrings:  580
+  CStrings:  578
CStrings:
- "ACMCredential - ACMCredentialDataPKITokenValidated"
- "ACMCredential - ACMCredentialDataPKITokenValidated2"
```

## powerdatad

> `/usr/libexec/powerdatad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0xa80` | `0xb40` | **`+0xc0`** |
| `__DATA.__data` | `0x208` | `0x248` | **`+0x40`** |
| `__TEXT.__cstring` | `0x6a9` | `0x6e9` | **`+0x40`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2043.0.13.502.1
+2043.0.31.0.0

-  CStrings:  408
+  CStrings:  414
CStrings:
+ "M0CPU"
+ "M1CPU"
+ "MACC0_V_T"
+ "MACC1_V_T"
+ "lts.m0cpu.plist"
+ "lts.m1cpu.plist"
```

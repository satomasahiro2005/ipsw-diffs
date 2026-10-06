## IOMFB_FDR_Loader

> `/usr/bin/IOMFB_FDR_Loader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34e34` | `0x34878` | **`-0x5bc`** |
| `__TEXT.__cstring` | `0x8e8d` | `0x8ec9` | **`+0x3c`** |
| `__TEXT.__gcc_except_tab` | `0x3d8` | `0x3d4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-700.50.72.0.0
+700.50.80.0.0

-  Functions: 530
+  Functions: 531

-  CStrings:  1063
+  CStrings:  1064
CStrings:
+ "Parser i: PDC RR inheriting NR bin interp: bin_low=%u t=%g\n"
```

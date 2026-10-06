## mediaplaybackd

> `/usr/libexec/mediaplaybackd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x40` | `—` | **`-0x40`** |
| `__TEXT.__text` | `0x1b0` | `0x178` | **`-0x38`** |
| `__TEXT.__cstring` | `0x48` | `0x1e` | **`-0x2a`** |
| `__DATA.__common` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0xd0` | `0xc0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x68` | `0x60` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3350.71.2.11.1
+3350.75.2.0.0

-  Symbols:   17
-  CStrings:  5
+  Symbols:   15
+  CStrings:  3
Symbols:
- ___CFConstantStringClassReference
- _fig_note_initialize_category_with_default_work_cf
Functions:
~ sub_100000b38 -> sub_100000a50 : 432 -> 376
CStrings:
- "com.apple.coremedia"
- "mediaplaybackd_trace"
```

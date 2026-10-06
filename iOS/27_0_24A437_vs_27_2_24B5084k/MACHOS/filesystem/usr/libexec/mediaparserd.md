## mediaparserd

> `/usr/libexec/mediaparserd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `—` | `0x40` | **`+0x40`** |
| `__TEXT.__text` | `0x160` | `0x198` | **`+0x38`** |
| `__TEXT.__cstring` | `0x1c` | `0x44` | **`+0x28`** |
| `__DATA.__common` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xa0` | `0xb0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x50` | `0x58` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3350.77.1.6.0
+3385.7.1.0.0

-  Symbols:   13
-  CStrings:  3
+  Symbols:   15
+  CStrings:  5
Symbols:
+ ___CFConstantStringClassReference
+ _fig_note_initialize_category_with_default_work_cf
Functions:
~ sub_1000008b8 -> sub_1000009a0 : 352 -> 408
CStrings:
+ "com.apple.coremedia"
+ "mediaparserd_trace"
```

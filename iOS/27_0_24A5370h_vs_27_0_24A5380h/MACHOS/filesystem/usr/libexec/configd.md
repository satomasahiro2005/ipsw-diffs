## configd

> `/usr/libexec/configd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68b8c` | `0x68ab0` | **`-0xdc`** |
| `__TEXT.__oslogstring` | `0x562c` | `0x564d` | **`+0x21`** |
| `__DATA_CONST.__got` | `0x6b8` | `0x6c8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x24f0` | `0x24e0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x1288` | `0x1280` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xa30` | `0xa28` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1438.0.0.0.0
+1441.0.0.0.0

-  Functions: 956
-  Symbols:   820
-  CStrings:  1667
+  Functions: 955
+  Symbols:   819
+  CStrings:  1668
Symbols:
- _CFArrayReplaceValues
CStrings:
+ "invalid pattern length %ld > %ld"
```

## hangreporter

> `/usr/libexec/hangreporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26120` | `0x26bac` | **`+0xa8c`** |
| `__DATA_CONST.__const` | `0x1680` | `0x16f8` | **`+0x78`** |
| `__TEXT.__cstring` | `0x431b` | `0x4378` | **`+0x5d`** |
| `__TEXT.__oslogstring` | `0x4d4f` | `0x4d97` | **`+0x48`** |
| `__TEXT.__const` | `0x2e0` | `0x2b0` | **`-0x30`** |
| `__TEXT.__gcc_except_tab` | `0xc94` | `0xcc4` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x5320` | `0x5340` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x3480` | `0x3460` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x600` | `0x618` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xf20` | `0xf30` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x7a0` | `0x7a8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x136c` | `0x1374` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0x5c9a` | `0x5c96` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`

### Other Changes

```diff

-426.0.0.0.0
+430.0.0.0.0

-  Functions: 757
-  Symbols:   334
-  CStrings:  2137
+  Functions: 766
+  Symbols:   335
+  CStrings:  2141
Symbols:
+ _objc_retain_x5
CStrings:
+ "Failed to open tailspin file %@ to write App Launch extended attributes"
+ "allTaskingPrefNames"
+ "hangtracer.event_end"
+ "hangtracer.event_start"
+ "hangtracer.event_type"
+ "v16@?0@?<v@?@\"NSString\"@\"NSString\">8"
+ "v24@?0@\"NSString\"8@\"NSString\"16"
- "hangtracer.hang_end"
- "hangtracer.hang_start"
- "setDisplayKernelFrames:"
```

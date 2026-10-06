## thermalmonitord

> `/usr/libexec/thermalmonitord`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x52564` | `0x526b0` | **`+0x14c`** |
| `__TEXT.__oslogstring` | `0x9d54` | `0x9e28` | **`+0xd4`** |
| `__TEXT.__objc_stubs` | `0x4f00` | `0x4f20` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x8388` | `0x839a` | **`+0x12`** |
| `__TEXT.__auth_stubs` | `0x13d0` | `0x13e0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1988` | `0x1990` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xa00` | `0xa08` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1230` | `0x1238` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2083.0.0.0.0
+2087.40.7.0.0

-  Functions: 2000
-  Symbols:   416
-  CStrings:  3744
+  Functions: 2001
+  Symbols:   417
+  CStrings:  3748
Symbols:
+ _objc_retain_x20
CStrings:
+ "<Error> Thermal config: %s exists but could not be loaded, falling back to device class default"
+ "<Notice> Thermal config source: device class default (%s)"
+ "<Notice> Thermal config source: product-specific plist %s"
+ "fileExistsAtPath:"
```

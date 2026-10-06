## perfdiagsselfenabled

> `/usr/libexec/perfdiagsselfenabled`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc690` | `0xc6fc` | **`+0x6c`** |
| `__TEXT.__const` | `0x23c` | `0x20c` | **`-0x30`** |
| `__TEXT.__objc_methname` | `0x34a7` | `0x34bb` | **`+0x14`** |
| `__TEXT.__objc_methlist` | `0xae4` | `0xaf0` | **`+0xc`** |
| `__TEXT.__cstring` | `0x14b6` | `0x14c0` | **`+0xa`** |
| `__DATA.__objc_selrefs` | `0x788` | `0x790` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-426.0.0.0.0
+430.0.0.0.0

-  Functions: 321
+  Functions: 322

-  CStrings:  842
+  CStrings:  843
CStrings:
+ "allTaskingPrefNames"
+ "com.apple.chrono.WidgetRenderer-"
- "WidgetRenderer-Default"
```

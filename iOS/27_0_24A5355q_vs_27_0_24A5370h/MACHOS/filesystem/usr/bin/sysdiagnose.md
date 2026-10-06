## sysdiagnose

> `/usr/bin/sysdiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x5d9` | `0x5f9` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xac` | `0xbc` | **`+0x10`** |
| `__TEXT.__text` | `0x3f8c` | `0x3f9c` | **`+0x10`** |
| `__DATA.__bss` | `0xa8` | `0xb0` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x238` | `0x240` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methtype`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1587.0.0.0.0
+1593.0.0.0.0

-  Functions: 83
+  Functions: 84

-  CStrings:  221
+  CStrings:  222
CStrings:
+ "setInternalDirectoryForTesting:"
```

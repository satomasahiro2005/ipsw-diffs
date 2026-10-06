## dyld

> `/System/ExclaveKit/usr/lib/dyld`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5bb58` | `0x5bc38` | **`+0xe0`** |
| `__DATA.__bss` | `0xba3f8` | `0xba408` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1e80` | `0x1e88` | **`+0x8`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH_CONST.__const`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_DIRTY.__all_image_info`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-27059.3.0.0.0
-  Functions: 2744
-  Symbols:   2420
+27060.1.0.0.0
+  Functions: 2746
+  Symbols:   2422
Symbols:
+ _plat_common_initialize_stdio
+ _xrt_dyld_setup_stdio
CStrings:
+ "27060.1"
- "27059.3"
```

## timed

> `/usr/libexec/timed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x174bc` | `0x17734` | **`+0x278`** |
| `__TEXT.__oslogstring` | `0x2c1b` | `0x2c6c` | **`+0x51`** |
| `__DATA_CONST.__cfstring` | `0x2b20` | `0x2b60` | **`+0x40`** |
| `__TEXT.__cstring` | `0x20a1` | `0x20d4` | **`+0x33`** |
| `__DATA_CONST.__const` | `0xe48` | `0xe68` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x26c0` | `0x26e0` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x5d0` | `0x5e8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x5e8` | `0x600` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1d8` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x2550` | `0x255c` | **`+0xc`** |
| `__DATA.__bss` | `0x140` | `0x148` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xb40` | `0xb48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-340.0.8.0.0
+340.0.11.0.0

-  Functions: 614
+  Functions: 618

-  CStrings:  1284
+  CStrings:  1289
CStrings:
+ "340.0.11"
+ "Received request for async auto time status"
+ "Returning best effort time to client"
+ "TMGetBestEffortTime"
+ "TMIsAutomaticTimeEnabledAsync"
+ "reliability"
- "340.0.8"
```

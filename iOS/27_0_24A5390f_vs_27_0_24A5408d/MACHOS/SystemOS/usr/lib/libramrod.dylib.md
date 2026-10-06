## libramrod.dylib

> `/usr/lib/libramrod.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeec34` | `0xeedb4` | **`+0x180`** |
| `__TEXT.__cstring` | `0x2bb6f` | `0x2bbc5` | **`+0x56`** |
| `__AUTH_CONST.__cfstring` | `0xc3a0` | `0xc3c0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x29d3` | `0x29f1` | **`+0x1e`** |
| `__DATA.__bss` | `0x888` | `0x8a0` | **`+0x18`** |
| `__TEXT.__const` | `0x79100` | `0x79110` | **`+0x10`** |
| `__DATA.__data` | `0x2598` | `0x2590` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xcc8` | `0xcd0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1194` | `0x119c` | **`+0x8`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH.__objc_data`
- `__AUTH_CONST.__auth_got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3696.0.7.0.0
+3696.0.12.0.3

-  Functions: 2860
-  Symbols:   1885
-  CStrings:  6356
+  Functions: 2862
+  Symbols:   1886
+  CStrings:  6360
Symbols:
+ _Img4EncodeItemCopyAndTransferBuffer
CStrings:
+ "Will use display %s (ctx %d)\n"
+ "aux image path set: %s\n"
+ "ctx[%d] rotation: %d\n"
+ "display-boot-rotation (MG) = %d\n"
+ "hasExclusiveUSBHostDeviceMode"
+ "usb-host-device-exclusive"
- "Will use display %s\n"
- "display-boot-rotation = %d\n"
```

## TextRecognition

> `/System/Library/PrivateFrameworks/TextRecognition.framework/TextRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x213310` | `0x21348c` | **`+0x17c`** |
| `__TEXT.__oslogstring` | `0x5193` | `0x5290` | **`+0xfd`** |
| `__TEXT.__eh_frame` | `0xa244` | `0xa27c` | **`+0x38`** |
| `__DATA.__bss` | `0x3020` | `0x3030` | **`+0x10`** |
| `__DATA.__data` | `0x15c0` | `0x15d0` | **`+0x10`** |
| `__TEXT.__const` | `0x7a30` | `0x7a40` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1d30` | `0x1d40` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2104` | `0x2110` | **`+0xc`** |
| `__TEXT.__cstring` | `0x1c0fb` | `0x1c102` | **`+0x7`** |
| `__TEXT.__swift5_typeref` | `0x29f2` | `0x29f6` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__ustring`

### Other Changes

```diff

-446.11.0.0.0
+446.13.0.0.0

-  Functions: 8698
-  Symbols:   8800
-  CStrings:  11304
+  Functions: 8700
+  Symbols:   8801
+  CStrings:  11307
Symbols:
+ GCC_except_table113
+ GCC_except_table131
+ GCC_except_table74
+ GCC_except_table75
+ GCC_except_table92
+ _posix_memalign
- GCC_except_table106
- GCC_except_table111
- GCC_except_table140
- GCC_except_table93
- _malloc
CStrings:
+ "CRCreateIOSurfacePixelBufferFromPixelBuffer: CVPixelBufferCreate failed."
+ "CRCreateIOSurfacePixelBufferFromPixelBuffer: skipping copy (NULL base address or insufficient destination stride)."
+ "[CRImage initARGB8888WithCVPixelBuffer:] vImageCopyBuffer failed"
```

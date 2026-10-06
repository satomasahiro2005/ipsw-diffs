## libHSFilerDynamic.dylib

> `/usr/lib/libHSFilerDynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34720` | `0x347a0` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x2bb0` | `0x2c14` | **`+0x64`** |
| `__TEXT.__const` | `0x2158` | `0x2160` | **`+0x8`** |

### Other Changes

```diff

-1576.0.0.0.0
+1580.0.0.0.0

-  CStrings:  379
+  CStrings:  380
Functions:
~ __ZN22HSFilerRT_Internal_INT13readFile_syncENSt3__110shared_ptrIN18HSFilerRT_Internal7SessionEEERKNS0_12basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEEmNS0_8functionIFvPKvmEEE : 2412 -> 2540
CStrings:
+ "error: BB reported actual_file_size_bytes_t7 (%zu) > preallocated fileSize (%zu) for session (%llu)"
```

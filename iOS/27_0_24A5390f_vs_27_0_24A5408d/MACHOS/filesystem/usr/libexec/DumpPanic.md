## DumpPanic

> `/usr/libexec/DumpPanic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b194` | `0x2b414` | **`+0x280`** |
| `__TEXT.__oslogstring` | `0x48d8` | `0x49a8` | **`+0xd0`** |
| `__TEXT.__gcc_except_tab` | `0xbb8` | `0xbdc` | **`+0x24`** |
| `__TEXT.__objc_stubs` | `0x2640` | `0x2660` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x8d0` | `0x8e8` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x1fc4` | `0x1fdb` | **`+0x17`** |
| `__DATA.__objc_selrefs` | `0xb00` | `0xb08` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2a8` | `0x2b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-37.0.0.0.0
+37.0.1.0.0

-  Functions: 863
+  Functions: 870

-  CStrings:  1334
+  CStrings:  1340
CStrings:
+ "Empty RTKit crashlog data"
+ "Failed to encode RTKit crashlog data to base64"
+ "Failed to process RTKit crashlog data"
+ "Invalid parameters for RTKit crashlog processing"
+ "Successfully processed RTKit crashlog data (%zu bytes)"
+ "useCrashlogContainers:"
```

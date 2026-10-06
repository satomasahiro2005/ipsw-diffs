## Diagnostic-6004

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-6004.appex/Diagnostic-6004`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14868` | `0x149a4` | **`+0x13c`** |
| `__TEXT.__objc_stubs` | `0xde0` | `0xe20` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x380` | `0x3a0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1310` | `0x1330` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x500` | `0x510` | **`+0x10`** |
| `__TEXT.__cstring` | `0xa4c` | `0xa5c` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2c0` | `0x2c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 478
-  Symbols:   216
-  CStrings:  383
+  Functions: 476
+  Symbols:   217
+  CStrings:  387
Symbols:
+ _EXDisplayPipeOpenDisplay
+ _OBJC_CLASS_$_NSMutableArray
- _EXDisplayPipeOpen
CStrings:
+ "Returning %ld stat sets"
+ "Stats found on index %u."
+ "addObject:"
+ "displayIndex"
+ "numberWithUnsignedInt:"
- "Failed to open ExDisplayPipe client for status!"
```

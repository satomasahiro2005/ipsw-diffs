## Diagnostic-8389

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8389.appex/Diagnostic-8389`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1deb0` | `0x1dffc` | **`+0x14c`** |
| `__TEXT.__objc_stubs` | `0xb20` | `0xb60` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x360` | `0x380` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x15fd` | `0x161d` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x4f0` | `0x500` | **`+0x10`** |
| `__TEXT.__cstring` | `0x11bd` | `0x11cd` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x230` | `0x238` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x18f` | `0x190` | **`+0x1`** |

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
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 857
-  Symbols:   197
-  CStrings:  447
+  Functions: 855
+  Symbols:   198
+  CStrings:  451
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

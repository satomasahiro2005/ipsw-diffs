## Diagnostic-8246

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8246.appex/Diagnostic-8246`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x50f0` | `0x5228` | **`+0x138`** |
| `__DATA_CONST.__cfstring` | `0x480` | `0x4a0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x18e0` | `0x1900` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1b47` | `0x1b5e` | **`+0x17`** |
| `__TEXT.__cstring` | `0x1c8` | `0x1d5` | **`+0xd`** |
| `__DATA.__objc_selrefs` | `0x800` | `0x808` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x52d` | `0x52e` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 139
+  Functions: 138

-  CStrings:  478
+  CStrings:  481
Symbols:
+ _EXDisplayPipeOpenDisplay
- _EXDisplayPipeOpen
CStrings:
+ "Returning %ld stat sets"
+ "Stats found on index %u."
+ "displayIndex"
+ "numberWithUnsignedInt:"
- "Failed to open ExDisplayPipe client for status!"
```

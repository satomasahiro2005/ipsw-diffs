## Diagnostic-4153

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-4153.appex/Diagnostic-4153`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8dd0` | `0x8f84` | **`+0x1b4`** |
| `__DATA_CONST.__cfstring` | `0x8c0` | `0x900` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3c1` | `0x3e2` | **`+0x21`** |
| `__TEXT.__objc_stubs` | `0x27c0` | `0x27e0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x30f2` | `0x3109` | **`+0x17`** |
| `__DATA.__objc_selrefs` | `0xd18` | `0xd20` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x200` | `0x208` | **`+0x8`** |
| `__TEXT.__const` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1e0` | `0x1d8` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0x3bd` | `0x3be` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 220
-  Symbols:   178
-  CStrings:  763
+  Functions: 219
+  Symbols:   180
+  CStrings:  767
Symbols:
+ _AVCaptureDeviceTypeBuiltInRenoUltraWideCamera
+ _DAIdentifierInnerFrontSuperWide
+ _EXDisplayPipeOpenDisplay
- _EXDisplayPipeOpen
CStrings:
+ "InnerFrontSuperWide"
+ "Returning %ld stat sets"
+ "Stats found on index %u."
+ "displayIndex"
+ "numberWithUnsignedInt:"
- "Failed to open ExDisplayPipe client for status!"
```

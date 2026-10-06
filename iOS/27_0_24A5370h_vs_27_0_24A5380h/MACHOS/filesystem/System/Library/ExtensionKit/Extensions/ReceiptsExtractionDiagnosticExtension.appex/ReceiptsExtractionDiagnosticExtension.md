## ReceiptsExtractionDiagnosticExtension

> `/System/Library/ExtensionKit/Extensions/ReceiptsExtractionDiagnosticExtension.appex/ReceiptsExtractionDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77f8` | `0x7c78` | **`+0x480`** |
| `__TEXT.__objc_stubs` | `0x480` | `0x4c0` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x3a8` | `0x3d1` | **`+0x29`** |
| `__TEXT.__cstring` | `0x4ee` | `0x50e` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x140` | `0x150` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1a0` | `0x1a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-362.0.0.0.0
+365.0.0.0.0

-  Functions: 85
+  Functions: 86

-  CStrings:  72
+  CStrings:  74
CStrings:
+ "creationDate"
+ "lastExtractionFailureReason"
```

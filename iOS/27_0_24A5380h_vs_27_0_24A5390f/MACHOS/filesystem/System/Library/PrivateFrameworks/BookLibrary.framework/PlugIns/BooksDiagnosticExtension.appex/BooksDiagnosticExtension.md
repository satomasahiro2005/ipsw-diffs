## BooksDiagnosticExtension

> `/System/Library/PrivateFrameworks/BookLibrary.framework/PlugIns/BooksDiagnosticExtension.appex/BooksDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21a0` | `0x23dc` | **`+0x23c`** |
| `__TEXT.__objc_methname` | `0x854` | `0x8e4` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x900` | `0x980` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x5c0` | `0x600` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x158` | `0x17c` | **`+0x24`** |
| `__DATA.__objc_selrefs` | `0x248` | `0x268` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3c1` | `0x3d8` | **`+0x17`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2306.0.0.0.0
+2309.0.0.0.0

-  Functions: 33
+  Functions: 36

-  CStrings:  144
+  CStrings:  150
Functions:
~ sub_1000018f4 : 680 -> 732
+ sub_100002360
+ sub_100002650
+ sub_100002780
CStrings:
+ "JetPackDiagnostics"
+ "_appendJetPackDiagnosticsToArray:"
+ "_getJetPackDiagnosticsPersistentStoreDirectoryWithContainer:"
+ "_getTmpDirectoryWithContainer:"
+ "fileExistsAtPath:"
+ "tmp"
```

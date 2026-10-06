## PhotosDiagnostics

> `/System/Library/PrivateFrameworks/PhotoLibraryServices.framework/PlugIns/PhotosDiagnostics.appex/PhotosDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf70` | `0x1090` | **`+0x120`** |
| `__DATA_CONST.__cfstring` | `0x2c0` | `0x340` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x4c0` | `0x540` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x422` | `0x480` | **`+0x5e`** |
| `__TEXT.__cstring` | `0x25a` | `0x2b0` | **`+0x56`** |
| `__DATA.__objc_selrefs` | `0x158` | `0x178` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x230` | `0x250` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x90` | `0xa8` | **`+0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `0x18` | `0x30` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x128` | `0x138` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x68` | `0x78` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xb0` | `0xb8` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0xce` | `0xd1` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-910.33.102.0.0
+912.0.111.0.0

-  Functions: 15
-  Symbols:   64
-  CStrings:  95
+  Functions: 16
+  Symbols:   69
+  CStrings:  103
Symbols:
+ _CPLLibraryPathsKey
+ _OBJC_CLASS_$_NSSecurityScopedURLWrapper
+ _OBJC_CLASS_$_NSURL
+ _objc_release_x24
+ _objc_release_x25
CStrings:
+ "@36@0:8B16@20@28"
+ "LibraryURL"
+ "_libraryURLWrapperFromParameters:"
+ "com.apple.campo"
+ "com.apple.intelligencecontextd"
+ "com.apple.intelligenceflowd"
+ "fileURLWithPath:"
+ "firstObject"
+ "initWithURL:"
+ "photosDiagnosticIncludingDatabases:bundleID:libraryURLWrapper:"
- "@28@0:8B16@20"
- "photosDiagnosticIncludingDatabases:bundleID:"
```

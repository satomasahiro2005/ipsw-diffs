## com.apple.Photos.CPLDiagnose

> `/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/XPCServices/com.apple.Photos.CPLDiagnose.xpc/com.apple.Photos.CPLDiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e17c` | `0x1e378` | **`+0x1fc`** |
| `__TEXT.__objc_stubs` | `0x4300` | `0x4380` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x4e85` | `0x4eed` | **`+0x68`** |
| `__TEXT.__auth_stubs` | `0xf10` | `0xf60` | **`+0x50`** |
| `__TEXT.__cstring` | `0x6fc7` | `0x700e` | **`+0x47`** |
| `__TEXT.__gcc_except_tab` | `0x3b4` | `0x3f0` | **`+0x3c`** |
| `__DATA_CONST.__auth_got` | `0x798` | `0x7c0` | **`+0x28`** |
| `__DATA_CONST.__const` | `0xc38` | `0xc60` | **`+0x28`** |
| `__DATA.__objc_const` | `0x2b60` | `0x2b80` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1440` | `0x1460` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1f40` | `0x1f50` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x6f8` | `0x708` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x6e8` | `0x6f7` | **`+0xf`** |
| `__DATA.__objc_ivar` | `0x210` | `0x214` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0

-  Functions: 703
-  Symbols:   391
-  CStrings:  2021
+  Functions: 705
+  Symbols:   396
+  CStrings:  2028
Symbols:
+ _objc_retain_x27
+ _objc_retain_x28
+ _sscanf
+ _tcgetattr
+ _tcsetattr
CStrings:
+ "%s options: %@"
+ "-[CPLDiagnoseService runDiagnoseWithOptions:replyHandler:]"
+ "_savedColumn"
+ "currentColumn"
+ "startAccessingSecurityScopedResource"
+ "stopAccessingSecurityScopedResource"
+ "url"
```

## PhotosDiagnostics

> `/System/Library/PrivateFrameworks/PhotoLibraryServices.framework/PlugIns/PhotosDiagnostics.appex/PhotosDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13d8` | `0x160c` | **`+0x234`** |
| `__TEXT.__objc_stubs` | `0x740` | `0x7c0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x2eb` | `0x361` | **`+0x76`** |
| `__TEXT.__oslogstring` | `0x1b7` | `0x1f1` | **`+0x3a`** |
| `__TEXT.__objc_methname` | `0x5db` | `0x602` | **`+0x27`** |
| `__DATA.__objc_selrefs` | `0x1f8` | `0x218` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x360` | `0x380` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x290` | `0x2b0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x158` | `0x168` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xc0` | `0xd0` | **`+0x10`** |
| `__TEXT.__const` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc0` | `0xb8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0

+  - /System/Library/PrivateFrameworks/PhotoLibraryServicesCore.framework/PhotoLibraryServicesCore

-  Symbols:   77
-  CStrings:  124
+  Symbols:   81
+  CStrings:  134
Symbols:
+ _CPLCustomBundleIDKey
+ _OBJC_CLASS_$_PLFilePathDescription
+ _objc_retain_x26
+ _objc_retain_x27
Functions:
~ sub_100001bbc -> sub_100001c3c : 948 -> 1260
~ sub_100001f70 -> sub_100002128 : 392 -> 644
CStrings:
+ "%s %@"
+ "%s returning %{public}@"
+ "(null)"
+ "-[PhotosDiagnosticsExtension _bundleIDFromParameters:]"
+ "-[PhotosDiagnosticsExtension attachmentsForParameters:]"
+ "array"
+ "copy"
+ "descriptionWithFileURL:"
+ "libraryURLWrapper.url is %@"
+ "url"
```

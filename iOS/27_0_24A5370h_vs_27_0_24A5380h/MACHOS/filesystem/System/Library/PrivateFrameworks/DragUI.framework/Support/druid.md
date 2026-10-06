## druid

> `/System/Library/PrivateFrameworks/DragUI.framework/Support/druid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ec0c` | `0x2ef74` | **`+0x368`** |
| `__TEXT.__auth_stubs` | `0xe20` | `0xe60` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x7ea0` | `0x7ee0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1567` | `0x1592` | **`+0x2b`** |
| `__TEXT.__objc_methname` | `0xc029` | `0xc051` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x720` | `0x740` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x1080` | `0x10a0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x3a8` | `0x3c0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x4c8` | `0x4e0` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x2978` | `0x2988` | **`+0x10`** |
| `__DATA.__bss` | `0x358` | `0x360` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x38ec` | `0x38f4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd30` | `0xd38` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-9127.0.68.0.0
+9127.0.72.0.0

+  - /System/Library/Frameworks/Security.framework/Security

-  Functions: 1368
-  Symbols:   382
-  CStrings:  2740
+  Functions: 1369
+  Symbols:   389
+  CStrings:  2743
Symbols:
+ _CFArrayGetTypeID
+ _CFGetTypeID
+ _PBMetadataEstimatedDisplayedSizeKey
+ _PBMetadataPreferredPresentationStyleKey
+ _PBMetadataSuggestedNameKey
+ _SecTaskCopyValueForEntitlement
+ _SecTaskCreateWithAuditToken
CStrings:
+ "arrayValueForEntitlement:"
+ "com.apple.Pasteboard.allowed-metadata-keys"
+ "setWithArray:"
```

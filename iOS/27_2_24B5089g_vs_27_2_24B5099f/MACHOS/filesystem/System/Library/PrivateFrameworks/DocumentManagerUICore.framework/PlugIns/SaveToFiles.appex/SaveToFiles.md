## SaveToFiles

> `/System/Library/PrivateFrameworks/DocumentManagerUICore.framework/PlugIns/SaveToFiles.appex/SaveToFiles`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59b8` | `0x5e4c` | **`+0x494`** |
| `__TEXT.__objc_stubs` | `0x13a0` | `0x14a0` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x1716` | `0x17e2` | **`+0xcc`** |
| `__TEXT.__cstring` | `0x4d3` | `0x593` | **`+0xc0`** |
| `__DATA_CONST.__cfstring` | `0x300` | `0x360` | **`+0x60`** |
| `__DATA.__objc_const` | `0x5b8` | `0x5f8` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x6a0` | `0x6e0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0xd8` | `0x98` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x570` | `0x598` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x404` | `0x42c` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1f8` | `0x210` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x800` | `0x810` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x30` | `0x38` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x410` | `0x418` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1a8` | `0x1b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-401.1.5.0.0
+403.1.8.0.0

+  - /System/Library/Frameworks/FileProvider.framework/FileProvider

-  Functions: 135
-  Symbols:   194
-  CStrings:  328
+  Functions: 139
+  Symbols:   196
+  CStrings:  342
Symbols:
+ _FPURLMightBeInFileProvider
+ _OBJC_CLASS_$_NSUUID
CStrings:
+ "No security-scoped claim for %@, copying instead"
+ "Request already completed, discarding temporary folder %@"
+ "Request already completed, discarding written file %@"
+ "URLByAppendingPathComponent:isDirectory:"
+ "UUID"
+ "UUIDString"
+ "_didReleaseLoadedItems"
+ "_registerSecurityScopedURL:"
+ "_registerTemporaryDirectory:"
+ "_releaseLoadedItems"
+ "_securityScopedURLsInUse"
+ "copy"
+ "removeAllObjects"
+ "v28@?0@\"NSURL\"8B16@\"NSError\"20"
```

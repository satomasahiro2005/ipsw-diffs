## PhotosDiagnostics

> `/System/Library/PrivateFrameworks/PhotoLibraryServices.framework/PlugIns/PhotosDiagnostics.appex/PhotosDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1090` | `0x13d8` | **`+0x348`** |
| `__TEXT.__objc_stubs` | `0x540` | `0x740` | **`+0x200`** |
| `__TEXT.__objc_methname` | `0x480` | `0x5db` | **`+0x15b`** |
| `__DATA.__objc_selrefs` | `0x178` | `0x1f8` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x163` | `0x1b7` | **`+0x54`** |
| `__TEXT.__auth_stubs` | `0x250` | `0x290` | **`+0x40`** |
| `__TEXT.__cstring` | `0x2b0` | `0x2eb` | **`+0x3b`** |
| `__DATA_CONST.__const` | `0xb8` | `0xe0` | **`+0x28`** |
| `__DATA_CONST.__objc_dictobj` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xb8` | `0xe0` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x138` | `0x158` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x340` | `0x360` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xa8` | `0xc0` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x78` | `0x88` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xb0` | `0xc0` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0xd1` | `0xdc` | **`+0xb`** |
| `__TEXT.__const` | `0x30` | `0x38` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-912.0.235.0.0
+916.40.110.0.0

+  - /System/Library/Frameworks/Photos.framework/Photos

-  Functions: 16
-  Symbols:   69
-  CStrings:  103
+  Functions: 19
+  Symbols:   77
+  CStrings:  124
Symbols:
+ _OBJC_CLASS_$_NSConstantDictionary
+ _OBJC_CLASS_$_NSMutableArray
+ _OBJC_CLASS_$_PHAsset
+ _OBJC_CLASS_$_PHFetchOptions
+ __os_log_error_impl
+ _objc_opt_new
+ _objc_release_x26
+ _objc_release_x27
CStrings:
+ "B24@0:8@16"
+ "No main file URL for asset %{public}@"
+ "Staged %lu of %lu requested assets for upload"
+ "TTRWorkflowAssetUploadIdentifiers"
+ "_includeSystemAndSyndicationLibrariesForBundleID:"
+ "_uploadAttachmentsWithParameters:"
+ "addObject:"
+ "addObjectsFromArray:"
+ "boolValue"
+ "count"
+ "enumerateObjectsUsingBlock:"
+ "fetchAssetsWithLocalIdentifiers:options:"
+ "initWithArray:"
+ "initWithPathURL:"
+ "localIdentifier"
+ "mainFileURL"
+ "objectForKey:"
+ "setIncludeGuestAssets:"
+ "setIncludeHiddenAssets:"
+ "setIncludeTrashedAssets:"
+ "v32@?0@\"PHAsset\"8Q16^B24"
```

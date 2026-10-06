## assetsd

> `/System/Library/Frameworks/AssetsLibrary.framework/Support/assetsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x180a4` | `0x1827c` | **`+0x1d8`** |
| `__TEXT.__objc_methname` | `0x554b` | `0x563c` | **`+0xf1`** |
| `__TEXT.__objc_methtype` | `0x91d` | `0x98d` | **`+0x70`** |
| `__DATA.__data` | `0x300` | `0x360` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x4a60` | `0x4ac0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x3fa6` | `0x3ff7` | **`+0x51`** |
| `__DATA_CONST.__cfstring` | `0xb20` | `0xb60` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x1468` | `0x1490` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xdec` | `0xe14` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x6bb` | `0x6e1` | **`+0x26`** |
| `__TEXT.__cstring` | `0x174a` | `0x175e` | **`+0x14`** |
| `__DATA.__objc_const` | `0x2cd0` | `0x2cd8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x540` | `0x548` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x80` | `0x7c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-910.27.103.0.0
+910.33.102.0.0

-  Functions: 357
+  Functions: 358

-  CStrings:  1247
+  CStrings:  1257
CStrings:
+ "@\"PLManagedAsset\"48@0:8@\"PHServerResourceRequestRunner\"16@\"NSURL\"24@\"PLPhotoLibrary\"32^@40"
+ "@48@0:8@16@24@32^@40"
+ "PHServerResourceRequestRunnerDelegate"
+ "[RM]: unable to access asset with object ID %{public}@ for client %{public}@: %@"
+ "authorizedAssetForObjectIDURL:relationshipKeyPathsForPrefetching:inLibrary:error:"
+ "connectionAuthorization"
+ "initWithLibraryServicesManager:connectionAuthorization:"
+ "initWithLibraryServicesManager:connectionAuthorization:shellObject:clientPid:"
+ "initWithTaskIdentifier:delegate:"
+ "master"
+ "modernResources"
+ "resourceRequestRunner:authorizedAssetForObjectIDURL:inLibrary:error:"
+ "trustedCallerBundleID"
- "_trustedCallerBundleID"
- "initWithLibraryServicesManager:shellObject:trustedCallerBundleID:clientPid:"
- "initWithTaskIdentifier:"
```

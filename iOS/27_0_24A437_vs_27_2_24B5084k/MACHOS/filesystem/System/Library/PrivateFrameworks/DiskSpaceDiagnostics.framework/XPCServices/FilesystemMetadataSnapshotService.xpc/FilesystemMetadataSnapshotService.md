## FilesystemMetadataSnapshotService

> `/System/Library/PrivateFrameworks/DiskSpaceDiagnostics.framework/XPCServices/FilesystemMetadataSnapshotService.xpc/FilesystemMetadataSnapshotService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14490` | `0x14ac8` | **`+0x638`** |
| `__TEXT.__oslogstring` | `0x19de` | `0x1b3c` | **`+0x15e`** |
| `__TEXT.__cstring` | `0x26d6` | `0x2800` | **`+0x12a`** |
| `__TEXT.__objc_methtype` | `0x5c7` | `0x638` | **`+0x71`** |
| `__TEXT.__objc_methname` | `0x2604` | `0x263c` | **`+0x38`** |
| `__TEXT.__objc_stubs` | `0x1a00` | `0x1a20` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x8fc` | `0x90c` | **`+0x10`** |
| `__DATA.__bss` | `0x128` | `0x130` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x7e0` | `0x7e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1023.0.4.0.0
+1023.40.3.0.0

-  Functions: 331
+  Functions: 335

-  CStrings:  951
+  CStrings:  963
CStrings:
+ "1023.40.3"
+ "@32@0:8@16^{__sFILE=*iiss{__sbuf=*i}i^v^?^?^?^?{__sbuf=*i}^{__sFILEX}i[3C][1C]{__sbuf=*i}iq}24"
+ "APFSIOC_LIST_ATTRIBUTION_TAGS failed for volume %s: %d (%s)"
+ "APFSIOC_LIST_ATTRIBUTION_TAGS failed for volume %s: %d (%s)\n"
+ "APFSIOC_LIST_ATTRIBUTION_TAGS returned no tags for volume %s without reporting the end of the listing"
+ "APFSIOC_LIST_ATTRIBUTION_TAGS returned no tags for volume %s without reporting the end of the listing\n"
+ "Collecting attribution tags for volume %s (%lu tags on volume)"
+ "Collecting attribution tags for volume %s (%lu tags on volume)\n"
+ "Failed to allocate buffer for listing attribution tags on volume %s"
+ "Failed to allocate buffer for listing attribution tags on volume %s\n"
+ "No owner listed for attribution tag hash %llu on file %s"
+ "_attributionTagOwnersForVolume:sharedLogFile:"
+ "_getAttributionTagPathsInDirectory:tagOwners:reply:"
+ "v40@0:8@16@24@?32"
- "1023.0.4"
- "_getAttributionTagPathsInDirectory:reply:"
```

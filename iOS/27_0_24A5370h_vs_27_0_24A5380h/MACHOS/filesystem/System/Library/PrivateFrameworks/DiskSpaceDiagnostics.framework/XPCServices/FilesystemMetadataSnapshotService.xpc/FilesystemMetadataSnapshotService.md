## FilesystemMetadataSnapshotService

> `/System/Library/PrivateFrameworks/DiskSpaceDiagnostics.framework/XPCServices/FilesystemMetadataSnapshotService.xpc/FilesystemMetadataSnapshotService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14240` | `0x1442c` | **`+0x1ec`** |
| `__TEXT.__cstring` | `0x2660` | `0x26c5` | **`+0x65`** |
| `__TEXT.__oslogstring` | `0x197f` | `0x19de` | **`+0x5f`** |
| `__TEXT.__const` | `0x190` | `0x178` | **`-0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1022.0.0.0.0
+1023.0.1.0.0

-  CStrings:  946
+  CStrings:  950
Functions:
~ sub_10000d104 : 8764 -> 9256
CStrings:
+ "1023.0.1"
+ "APFSIOC_GET_GRAFT_INFO failed for %s: %d (%s)"
+ "APFSIOC_GET_GRAFT_INFO failed for %s: %d (%s)\n"
+ "Skipping descendents of cryptex graft host at %s"
+ "Skipping descendents of cryptex graft host at %s\n"
- "1022"
```

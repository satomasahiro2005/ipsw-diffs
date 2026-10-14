## biomesyncd

> `/usr/libexec/biomesyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c544` | `0x4c8c4` | **`+0x380`** |
| `__TEXT.__objc_methname` | `0xa7b2` | `0xa8a9` | **`+0xf7`** |
| `__TEXT.__objc_stubs` | `0x8bc0` | `0x8c60` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x6ad4` | `0x6b29` | **`+0x55`** |
| `__TEXT.__objc_methlist` | `0x3cf4` | `0x3d44` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x2990` | `0x29b8` | **`+0x28`** |
| `__DATA.__objc_const` | `0x7708` | `0x7728` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1130` | `0x1140` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x450` | `0x458` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-258.0.0.0.0
+259.0.0.0.0

-  Functions: 1653
+  Functions: 1660

-  CStrings:  3120
+  CStrings:  3128
CStrings:
+ "TB,R,N,GisSyncSessionInFlight"
+ "adoptMultiStreamManager:"
+ "adoptPrimarySyncManager:"
+ "failed to rebuild the sync stream manager to adopt a rotated local device identifier"
+ "isSyncSessionInFlight"
+ "rebuildPrimaryUserSyncStreamManagerIfIdentifierRotationIsDue"
+ "shouldRotateLocalDeviceIdentifierForPeerStatusTracker:database:"
+ "syncSessionInFlight"
```

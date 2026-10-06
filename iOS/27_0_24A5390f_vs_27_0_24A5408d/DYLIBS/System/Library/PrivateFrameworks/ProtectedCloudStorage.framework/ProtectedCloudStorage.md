## ProtectedCloudStorage

> `/System/Library/PrivateFrameworks/ProtectedCloudStorage.framework/ProtectedCloudStorage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x4024` | `0x4089` | **`+0x65`** |
| `__TEXT.__text` | `0x6ddc8` | `0x6ddec` | **`+0x24`** |

### Other Changes

```diff

-1303.0.3.0.0
+1303.0.6.0.0

-  CStrings:  3795
+  CStrings:  3796
Functions:
~ ___42-[PCSCKKSSyncViewOperation checkTLKStatus]_block_invoke : 520 -> 556
CStrings:
+ "CKKS response for active views: not in circle"
+ "CKKS response for active views: wait for Octagon. This should resolve, proceeding with CKKS sync anyway"
- "CKKS response for active views: wait for Octagon"
```

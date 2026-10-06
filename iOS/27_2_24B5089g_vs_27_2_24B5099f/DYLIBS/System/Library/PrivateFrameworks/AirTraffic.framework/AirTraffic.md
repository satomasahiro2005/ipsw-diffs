## AirTraffic

> `/System/Library/PrivateFrameworks/AirTraffic.framework/AirTraffic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18bf0` | `0x18d68` | **`+0x178`** |
| `__AUTH_CONST.__cfstring` | `0x1da0` | `0x1de0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1510` | `0x1528` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1786` | `0x1774` | **`-0x12`** |
| `__TEXT.__const` | `0x68` | `0x60` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0x1541` | `0x1544` | **`+0x3`** |

### Other Changes

```diff

-4026.200.7.0.0
+4026.200.21.0.0

-  Symbols:   1643
-  CStrings:  427
+  Symbols:   1647
+  CStrings:  425
Symbols:
+ _mkdirat
+ _open
+ _renameatx_np
+ _unlinkat
Functions:
~ -[ATAirlock processCompletedAsset:] : 1788 -> 2164
CStrings:
+ "."
+ "/"
+ "Airlock moved %{public}@ to %{public}@ beneath AFC root"
+ "Could not create directory %{public}@ beneath AFC root: %{errno}d"
+ "Could not open AFC root %{public}@: %{errno}d"
+ "Failed to move completed file for asset %{public}@ after retry, error: %{errno}d (path '%{public}@')"
+ "Failed to move completed file for asset %{public}@ beneath AFC root, error: %{errno}d (path '%{public}@')"
+ "Failed to remove completed upload for asset %{public}@, error: %{public}@"
- "Airlock destination directory not present, creating %{public}@"
- "Airlock moved %{public}@ to %{pubic}@"
- "Cannot move asset outside of AFC root: %{public}@"
- "Could not create directory %{public}@, error: %{public}@"
- "Failed ro remove completed upload for asset %{public}@, error: %{public}@"
- "Failed to move completed file for asset %{public}@, error: %{public}@"
- "File already exists at %{public}@, removing"
- "Source %s: %{public}@, Destination %s: %{public}@"
- "does not exist"
- "exists"
```

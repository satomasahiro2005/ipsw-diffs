## AssetCacheLocatorService

> `/System/Library/PrivateFrameworks/AssetCacheServices.framework/XPCServices/AssetCacheLocatorService.xpc/AssetCacheLocatorService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fee0` | `0x1fea8` | **`-0x38`** |
| `__TEXT.__oslogstring` | `0x298f` | `0x297f` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-154.0.0.0.0
+156.0.0.0.0

-  CStrings:  1271
+  CStrings:  1270
Functions:
~ sub_1000086dc : 3920 -> 3864
CStrings:
+ "#%08x [%s] makeLocalAddresses -> localAddresses=%{private}@ gatewayIdentifiers=[%ld]%{private}@"
+ "#%08x [%s] makeLocalAddresses: defaultAddresses[%d]: ifaddr=%{private}@"
- "#%08x [%s] makeLocalAddresses -> localAddresses=%@ gatewayIdentifiers=[%ld]%{private}@"
- "#%08x [%s] makeLocalAddresses: %@"
- "#%08x [%s] makeLocalAddresses: defaultAddresses[%d]: ifaddr=%@"
```

## MapKit

> `/System/Library/Frameworks/MapKit.framework/MapKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x291310` | `0x2913f0` | **`+0xe0`** |
| `__DATA.__bss` | `0x4718` | `0x4720` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x14bc8` | `0x14bd0` | **`+0x8`** |

### Other Changes

```diff
Symbols:
+ __GEOConfigRemoveValue
- _GEOConfigSetArray
Functions:
~ +[_MXExtensionManager(Ridesharing) _maps_migrateRideBookingExtensionsFromLegacyStorageIfNeeded] : 4 -> 204
~ +[_MXExtensionManager(Ridesharing) _maps_updateRideBookingExtensions:] : 552 -> 576
```

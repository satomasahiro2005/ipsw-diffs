## DataDeliveryServices

> `/System/Library/PrivateFrameworks/DataDeliveryServices.framework/DataDeliveryServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29fb8` | `0x2a060` | **`+0xa8`** |
| `__TEXT.__oslogstring` | `0x3dbf` | `0x3dfd` | **`+0x3e`** |
| `__TEXT.__objc_methlist` | `0x2a64` | `0x2a7c` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x8e10` | `0x8e18` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1610` | `0x1618` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc90` | `0xc98` | **`+0x8`** |

### Other Changes

```diff

-114.0.0.0.0
+115.0.0.0.0

-  Functions: 1042
-  Symbols:   1938
-  CStrings:  561
+  Functions: 1043
+  Symbols:   1939
+  CStrings:  562
Symbols:
+ -[DDSAssetObserver notifyDelegateAssetsUpdatedForType:]
Functions:
+ -[DDSAssetObserver notifyDelegateAssetsUpdatedForType:]
CStrings:
+ "Notifying local delegate of asset update for type: %{public}@"
```

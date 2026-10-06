## DataDeliveryServices

> `/System/Library/PrivateFrameworks/DataDeliveryServices.framework/DataDeliveryServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29e48` | `0x29fb8` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x3d7d` | `0x3dbf` | **`+0x42`** |
| `__TEXT.__cstring` | `0x16e5` | `0x16c2` | **`-0x23`** |
| `__AUTH_CONST.__cfstring` | `0x19a0` | `0x1980` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0xc70` | `0xc90` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x330` | `0x338` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1608` | `0x1610` | **`+0x8`** |

### Other Changes

```diff

-113.0.0.0.0
+114.0.0.0.0

-  Symbols:   1937
+  Symbols:   1938
Symbols:
+ _OBJC_CLASS_$_RBSAcquisitionCompletionAttribute
+ _os_variant_has_internal_content
- _MGGetBoolAnswer
CStrings:
+ "FinishTaskNow"
+ "Skip update cycle due to UAF migration for asset type: %{public}@"
- "FinishTaskUninterruptable"
- "apple-internal-install"
```

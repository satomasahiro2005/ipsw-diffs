## UnifiedAssetFramework

> `/System/Library/PrivateFrameworks/UnifiedAssetFramework.framework/UnifiedAssetFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x778ac` | `0x77ddc` | **`+0x530`** |
| `__TEXT.__oslogstring` | `0xecfe` | `0xee16` | **`+0x118`** |
| `__TEXT.__cstring` | `0xb840` | `0xb87a` | **`+0x3a`** |
| `__TEXT.__objc_methlist` | `0x36c0` | `0x36d8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x26a0` | `0x26b0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x11f8` | `0x1208` | **`+0x10`** |

### Other Changes

```diff

-3600.70.1.0.0
+3600.74.1.0.0

-  Functions: 1457
-  Symbols:   2767
-  CStrings:  2114
+  Functions: 1460
+  Symbols:   2770
+  CStrings:  2119
Symbols:
+ -[UAFRootsV2AssetSet assetWithName:specifier:experiment:]
+ -[UAFRootsV2AssetSet availableExperimentalSpecifiersForExperiment:]
+ ___57-[UAFRootsV2AssetSet assetWithName:specifier:experiment:]_block_invoke
+ ___67-[UAFRootsV2AssetSet availableExperimentalSpecifiersForExperiment:]_block_invoke
- ___44-[UAFRootsV2AssetSet loadAssets:experiment:]_block_invoke_2
CStrings:
+ "%s %{public}@: Cannot resolve %{public}@ from roots V2 for %{public}@: lock not held"
+ "%s %{public}@: No Roots V2 asset for %{public}@, returning nil (exclusive)"
+ "%s %{public}@: No specifier for %{public}@ in roots V2 for %{public}@"
+ "%s %{public}@: Returning %{public}@ from Roots V2"
+ "-[UAFRootsV2AssetSet assetWithName:specifier:experiment:]"
```

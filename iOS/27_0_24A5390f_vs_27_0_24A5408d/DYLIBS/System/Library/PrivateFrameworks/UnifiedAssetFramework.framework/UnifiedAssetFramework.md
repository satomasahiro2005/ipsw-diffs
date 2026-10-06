## UnifiedAssetFramework

> `/System/Library/PrivateFrameworks/UnifiedAssetFramework.framework/UnifiedAssetFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xb87a` | `0xb871` | **`-0x9`** |
| `__TEXT.__text` | `0x77ddc` | `0x77de4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1208` | `0x1200` | **`-0x8`** |

### Other Changes

```diff

-3600.74.1.0.0
+3600.77.1.0.0
Symbols:
+ -[UAFAssetOriginReport _populateFromMAReport:error:]
- -[UAFAssetOriginReport _populateFromMAReport:error:errorOut:]
CStrings:
+ "-[UAFAssetOriginReport _populateFromMAReport:error:]"
- "-[UAFAssetOriginReport _populateFromMAReport:error:errorOut:]"
```

## MorphunAssets

> `/System/Library/PrivateFrameworks/MorphunAssets.framework/MorphunAssets`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8a18` | `0x8b08` | **`+0xf0`** |
| `__DATA.__bss` | `—` | `0x10` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x78` | `0x68` | **`-0x10`** |
| `__DATA.__data` | `0x8` | `0x10` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4c0` | `0x4c8` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x8` | `—` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2f8` | `0x2f0` | **`-0x8`** |

### Other Changes

```diff

-3600.35.1.0.0
+3600.36.1.0.0
Functions:
~ -[MorphunAssets(MorphunAssetsSubscription) referenceCountsFromSubscriptionView] : 620 -> 672
~ -[MorphunAssets(MorphunAssetsSubscription) isSubscribedToLocale:] : 224 -> 284
~ -[MorphunAssets(MorphunAssetsSubscription) listSubscriptions] : 4 -> 132
```

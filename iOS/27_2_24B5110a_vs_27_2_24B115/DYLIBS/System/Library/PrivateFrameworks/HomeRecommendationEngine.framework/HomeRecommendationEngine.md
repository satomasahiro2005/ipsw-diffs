## HomeRecommendationEngine

> `/System/Library/PrivateFrameworks/HomeRecommendationEngine.framework/HomeRecommendationEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23284` | `0x236dc` | **`+0x458`** |
| `__AUTH_CONST.__objc_const` | `0x54a8` | `0x5638` | **`+0x190`** |
| `__TEXT.__objc_methlist` | `0x29cc` | `0x2a7c` | **`+0xb0`** |
| `__AUTH_CONST.__const` | `0x1280` | `0x1300` | **`+0x80`** |
| `__DATA.__bss` | `0x2c0` | `0x2f0` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x1728` | `0x1748` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xa58` | `0xa78` | **`+0x20`** |
| `__DATA_CONST.__objc_catlist` | `0x78` | `0x80` | **`+0x8`** |

### Other Changes

```diff

-1269.2.5.1.4
+1269.2.5.1.5

-  Functions: 974
-  Symbols:   2054
+  Functions: 990
+  Symbols:   2075
Symbols:
+ -[HMMediaGroup(HRERecommendableObjectProtocol) hre_actionTypes]
+ -[HMMediaGroup(HRERecommendableObjectProtocol) hre_characteristicTypeForActionType:]
+ -[HMMediaGroup(HRERecommendableObjectProtocol) hre_characteristics]
+ -[HMMediaGroup(HRERecommendableObjectProtocol) hre_home]
+ -[HMMediaGroup(HRERecommendableObjectProtocol) hre_isActionable]
+ -[HMMediaGroup(HRERecommendableObjectProtocol) hre_isMediaObject]
+ -[HMMediaGroup(HRERecommendableObjectProtocol) hre_isVisible]
+ -[HMMediaGroup(HRERecommendableObjectProtocol) hre_matchingTypes]
+ -[HMMediaGroup(HRERecommendableObjectProtocol) hre_parentRoom]
+ -[HMMediaGroup(HRERecommendableObjectProtocol) hre_primaryType]
+ _OBJC_CLASS_$_HMMediaGroup
+ __OBJC_$_CATEGORY_HMMediaGroup_$_HRERecommendableObjectProtocol
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_HMMediaGroup_$_HRERecommendableObjectProtocol
+ __OBJC_$_PROP_LIST_HMMediaGroup_$_HRERecommendableObjectProtocol
+ __OBJC_CATEGORY_PROTOCOLS_$_HMMediaGroup_$_HRERecommendableObjectProtocol
+ ___61-[HMMediaGroup(HRERecommendableObjectProtocol) hre_isVisible]_block_invoke
+ ___63-[HMMediaGroup(HRERecommendableObjectProtocol) hre_actionTypes]_block_invoke
+ ___63-[HMMediaGroup(HRERecommendableObjectProtocol) hre_primaryType]_block_invoke_2
+ ___65-[HMMediaGroup(HRERecommendableObjectProtocol) hre_matchingTypes]_block_invoke
+ ___65-[HMMediaGroup(HRERecommendableObjectProtocol) hre_matchingTypes]_block_invoke_2
+ ___67-[HMMediaGroup(HRERecommendableObjectProtocol) hre_characteristics]_block_invoke_2
```

## NewsServicesInternal

> `/System/Library/PrivateFrameworks/NewsServicesInternal.framework/NewsServicesInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb60c` | `0xb6c4` | **`+0xb8`** |
| `__DATA_CONST.__objc_selrefs` | `0xd60` | `0xd70` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1e8` | `0x1f0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xd1c` | `0xd24` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x398` | `0x3a0` | **`+0x8`** |

### Other Changes

```diff

-5934.3.0.0.0
+5960.0.0.0.0

-  Functions: 345
-  Symbols:   792
+  Functions: 346
+  Symbols:   794
Symbols:
+ -[NSSArticleViewControllerInternal viewDidLayoutSubviews]
+ _CGSizeZero
Functions:
~ -[NSSArticleView layoutSubviews] : 1620 -> 1636
+ -[NSSArticleViewControllerInternal viewDidLayoutSubviews]
```

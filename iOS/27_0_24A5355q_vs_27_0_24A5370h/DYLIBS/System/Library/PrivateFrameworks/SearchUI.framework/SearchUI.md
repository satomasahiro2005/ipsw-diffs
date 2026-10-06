## SearchUI

> `/System/Library/PrivateFrameworks/SearchUI.framework/SearchUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf2460` | `0xf3198` | **`+0xd38`** |
| `__TEXT.__eh_frame` | `0x221c` | `0x230c` | **`+0xf0`** |
| `__AUTH_CONST.__const` | `0x2980` | `0x2a20` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x2805` | `0x2885` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x12198` | `0x12208` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x4780` | `0x47e0` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x79c` | `0x7ec` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xa158` | `0xa198` | **`+0x40`** |
| `__TEXT.__const` | `0x37f4` | `0x3824` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2850` | `0x2878` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x1dd48` | `0x1dd58` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x24d8` | `0x24e8` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x1bc` | `0x1c8` | **`+0xc`** |
| `__AUTH.__objc_data` | `0x5ca0` | `0x5ca8` | **`+0x8`** |
| `__AUTH_CONST.__auth_got` | `0x1870` | `0x1878` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x13f0` | `0x13f8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x994` | `0x99c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x12c` | `0x130` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x110` | `0x114` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-668.101.0.0.0
+672.1.0.0.0

-  Functions: 6908
-  Symbols:   11387
-  CStrings:  817
+  Functions: 6933
+  Symbols:   11396
+  CStrings:  818
Symbols:
+ -[SearchUIAppIconImage effectiveSize]
+ -[SearchUICallCommandHandler destinationApplicationBundleIdentifier]
+ -[SearchUICollectionView setScrollEnabled:]
+ -[SearchUICollectionViewController moveUpToTextField]
+ -[SearchUIImage shadowInsetRatio]
+ -[SearchUIQuickLookThumbnailImage shadowInsetRatio]
+ -[SearchUISportsFollowButtonItemGenerator fallbackToUnsupportedGameFollowingButtonForSFButtonItem:completionHandler:]
+ GCC_except_table103
+ ___98-[SearchUISportsFollowButtonItemGenerator generateSearchUIButtonItemsWithSFButtonItem:completion:]_block_invoke_6
+ ___block_descriptor_64_e8_32s40s48s56bs_e8_v12?0B8ls32l8s56l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e18_v16?0"NSNumber"8ls32l8s40l8s64l8s48l8s56l8
- GCC_except_table101
- ___block_descriptor_56_e8_32s40s48bs_e18_v16?0"NSNumber"8ls32l8s48l8s40l8
CStrings:
+ "Layout requested section %ld which is no longer in the snapshot (cached layout out of sync after purge); returning an empty section."
+ "app.slash"
- "hand.raised"
```

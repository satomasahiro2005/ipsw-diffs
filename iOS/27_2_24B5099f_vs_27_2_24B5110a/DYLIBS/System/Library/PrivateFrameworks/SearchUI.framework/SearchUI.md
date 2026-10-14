## SearchUI

> `/System/Library/PrivateFrameworks/SearchUI.framework/SearchUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf74e4` | `0xf7d10` | **`+0x82c`** |
| `__DATA.__data` | `0x2fec` | `0x305c` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x12530` | `0x12580` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x2570` | `0x25a8` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x1e148` | `0x1e178` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x4918` | `0x4948` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xa318` | `0xa340` | **`+0x28`** |
| `__TEXT.__const` | `0x3ac4` | `0x3ad4` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xd08` | `0xd0c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-685.1.8.200.0
+685.1.10.0.0

-  Functions: 7033
-  Symbols:   11527
-  CStrings:  832
+  Functions: 7053
+  Symbols:   11537
+  CStrings:  833
Symbols:
+ +[SearchUIAppIconCardSectionView contentLayoutMarginsFittingWidth:shouldFillAvailableSpace:]
+ -[SFAppIconCardSection(SearchUIGridSectionModel) searchUIGridSectionModel_groupInsetFor:backgroundStyle:]
+ -[SFAppIconCardSection(SearchUIGridSectionModel) searchUIGridSectionModel_maximumNumberOfVisibleCardSectionsForWidth:]
+ -[SFCardSection(SearchUIGridSectionModel) searchUIGridSectionModel_groupInsetFor:backgroundStyle:]
+ -[SFCardSection(SearchUIGridSectionModel) searchUIGridSectionModel_maximumNumberOfVisibleCardSectionsForWidth:]
+ -[SFLinkPresentationCardSection(SearchUIGridSectionModel) searchUIGridSectionModel_groupInsetFor:backgroundStyle:]
+ -[SearchUICollectionViewDataSource truncatedVisibleCardSectionsAsyncSectionModel:]
+ -[SearchUICollectionViewDataSource updatePositionalStylingForCell:atIndexPath:]
+ -[SearchUIGridSectionModel maximumNumberOfVisibleCardSectionsForWidth:]
+ -[SearchUIResultsCollectionViewController isApplyingTableModel]
+ -[SearchUIResultsCollectionViewController setIsApplyingTableModel:]
+ -[SearchUISectionModel maximumNumberOfVisibleCardSectionsForWidth:]
+ GCC_except_table30
+ _OBJC_IVAR_$_SearchUIResultsCollectionViewController._isApplyingTableModel
+ _SearchUINoMaximumVisibleCardSections
+ _swift_retain_x28
- +[SearchUIAppIconUtilities gridSectionLayoutMarginsFittingSize:shouldFillAvailableSpace:]
- +[SearchUIAppIconUtilities idealHorizontalSpacingBetweenAppIcons]
- -[SFAppIconCardSection(SearchUIGridSectionModel) searchUIGridSectionModel_groupInsetFor:]
- -[SFCardSection(SearchUIGridSectionModel) searchUIGridSectionModel_groupInsetFor:]
- -[SFLinkPresentationCardSection(SearchUIGridSectionModel) searchUIGridSectionModel_groupInsetFor:]
- _swift_retain_x27
CStrings:
+ "$"
```

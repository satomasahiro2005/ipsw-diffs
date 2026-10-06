## MobileSafari

> `/System/Library/PrivateFrameworks/MobileSafari.framework/MobileSafari`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4dc8ac` | `0x4e1554` | **`+0x4ca8`** |
| `__AUTH_CONST.__objc_const` | `0x3afd8` | `0x3b238` | **`+0x260`** |
| `__AUTH_CONST.__const` | `0x20b30` | `0x20d10` | **`+0x1e0`** |
| `__DATA_DIRTY.__data` | `0x16f8` | `0x1840` | **`+0x148`** |
| `__DATA_DIRTY.__objc_data` | `0x4950` | `0x4a78` | **`+0x128`** |
| `__TEXT.__objc_methlist` | `0x1c9c8` | `0x1cae8` | **`+0x120`** |
| `__DATA_CONST.__objc_selrefs` | `0x10288` | `0x10398` | **`+0x110`** |
| `__AUTH.__data` | `0x8088` | `0x7f98` | **`-0xf0`** |
| `__TEXT.__swift5_capture` | `0x7138` | `0x7220` | **`+0xe8`** |
| `__TEXT.__cstring` | `0x133c9` | `0x134a9` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x11c8c` | `0x11d64` | **`+0xd8`** |
| `__TEXT.__unwind_info` | `0x122b0` | `0x12388` | **`+0xd8`** |
| `__TEXT.__swift5_reflstr` | `0xc641` | `0xc701` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x10ed0` | `0x10e20` | **`-0xb0`** |
| `__DATA_CONST.__got` | `0x28f0` | `0x2998` | **`+0xa8`** |
| `__TEXT.__eh_frame` | `0x8dac` | `0x8e4c` | **`+0xa0`** |
| `__DATA.__data` | `0xe178` | `0xe208` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0xaac0` | `0xab40` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x6508` | `0x6578` | **`+0x70`** |
| `__TEXT.__const` | `0x1caa4` | `0x1cb14` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x77c0` | `0x7830` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x4599` | `0x45d9` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x9a88` | `0x9ac4` | **`+0x3c`** |
| `__TEXT.__ustring` | `0x2414` | `0x2440` | **`+0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x3900` | `0x3918` | **`+0x18`** |
| `__DATA_DIRTY.__common` | `0x240` | `0x258` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x438` | `0x44c` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x4d0` | `0x4e4` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x490` | `0x4a4` | **`+0x14`** |
| `__DATA.__bss` | `0x20a60` | `0x20a70` | **`+0x10`** |
| `__DATA.__common` | `0xce1` | `0xcd1` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x35c` | `0x36c` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1cc8` | `0x1cd4` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x95c` | `0x960` | **`+0x4`** |

### Other Changes

```diff

-625.1.20.10.3
+625.1.22.10.3

-  Functions: 26737
-  Symbols:   20214
-  CStrings:  2669
+  Functions: 26842
+  Symbols:   20234
+  CStrings:  2677
Symbols:
+ -[SFCapsuleNavigationBar navigationBarItemDidUpdateShowsPageFormatButton:]
+ -[SFNotifyMeWhenBanner _makeFeedbackButton]
+ -[SFPrivacyReportOverviewCellView groupStyle]
+ -[SFPrivacyReportOverviewCellView setGroupStyle:]
+ -[SFPrivacyReportOverviewCellView setNeedsUpdateHairlineConstraints]
+ -[SFPrivacyReportOverviewCellView updateConstraints]
+ -[SFPrivacyReportOverviewView groupStyle]
+ -[SFPrivacyReportOverviewView setGroupStyle:]
+ -[SFStartPageCollectionViewController invalidateCollectionViewLayout]
+ -[SFStartPageViewController invalidateCollectionViewLayout]
+ -[SFUnifiedTabBar itemsUseContentSafeAreaLayoutMargins]
+ -[SFUnifiedTabBar setItemsUseContentSafeAreaLayoutMargins:]
+ -[SFUnifiedTabBarItemArrangement _determineIndexOfStickySectionTitle]
+ -[SFUnifiedTabBarItemArrangement _enumerateSectionRangesUsingBlock:]
+ -[SFUnifiedTabBarItemArrangement indexOfStickySectionTitle]
+ -[SFUnifiedTabBarItemArrangement stickySectionTitle]
+ -[SFUnifiedTabBarItemView setUsesContentSafeAreaLayoutMargins:]
+ -[SFUnifiedTabBarItemView usesContentSafeAreaLayoutMargins]
+ -[SFUnifiedTabBarLayout _widthForItem:preferCached:]
+ GCC_except_table198
+ GCC_except_table202
+ GCC_except_table206
+ GCC_except_table218
+ _OBJC_CLASS_$_SFText
+ _OBJC_IVAR_$_SFNotifyMeWhenBanner._feedbackButton
+ _OBJC_IVAR_$_SFPrivacyReportOverviewCellView._groupStyle
+ _OBJC_IVAR_$_SFPrivacyReportOverviewCellView._hairlineConstraints
+ _OBJC_IVAR_$_SFPrivacyReportOverviewView._groupStyle
+ _OBJC_IVAR_$_SFUnifiedTabBar._itemsUseContentSafeAreaLayoutMargins
+ _OBJC_IVAR_$_SFUnifiedTabBarItemArrangement._indexOfStickySectionTitle
+ _OBJC_IVAR_$_SFUnifiedTabBarItemView._usesContentSafeAreaLayoutMargins
+ _WBSParsecDomainSafariStartPageRecentSearches
+ __SFBookmarkFeatureTextBackfillCompletedForAltDSIDKey
+ ___43-[SFNotifyMeWhenBanner _makeFeedbackButton]_block_invoke
+ ___43-[SFNotifyMeWhenBanner _makeFeedbackButton]_block_invoke_2
+ ___68-[SFUnifiedTabBarItemArrangement _enumerateSectionRangesUsingBlock:]_block_invoke
+ ___69-[SFUnifiedTabBarItemArrangement _determineIndexOfStickySectionTitle]_block_invoke
+ ___block_descriptor_40_e8_32s_e51_v40?0"SFUnifiedTabBarSection"8{_NSRange=QQ}16^B32ls32l8
+ ___block_descriptor_48_e8_32bs40r_e39_v32?0"SFUnifiedTabBarSection"8Q16^B24lr40l8s32l8
+ ___swift_closure_destructor.336Tm
+ ___swift_closure_destructor.342Tm
+ ___swift_closure_destructor.401Tm
+ ___swift_closure_destructor.404Tm
+ ___swift_closure_destructor.70Tm
+ ___swift_closure_destructor.74Tm
+ ___unnamed_65
+ _keypath_get_selector_feedbackDispatcher
+ _symbolic _____ So21WBSUserReportedActionV
- -[SFNotifyMeWhenBanner _makeFileRadarButton]
- -[SFNotifyMeWhenBanner invalidateBannerLayout]
- -[SFNotifyMeWhenBanner setLayoutMargins:]
- -[SFPrivacyReportOverviewCellView setUsesInsetStyle:]
- -[SFPrivacyReportOverviewView setUsesInsetStyle:]
- -[SFPrivacyReportOverviewView usesInsetStyle]
- -[SFUnifiedBarItemView setZOffsetWithinSection:]
- -[SFUnifiedBarItemView zOffsetWithinSection]
- GCC_except_table100
- GCC_except_table111
- GCC_except_table197
- GCC_except_table201
- GCC_except_table205
- GCC_except_table217
- _OBJC_IVAR_$_SFNotifyMeWhenBanner._fileRadarButton
- _OBJC_IVAR_$_SFPrivacyReportOverviewCellView._usesInsetStyle
- _OBJC_IVAR_$_SFPrivacyReportOverviewView._usesInsetStyle
- _OBJC_IVAR_$_SFUnifiedBarItemView._zOffsetWithinSection
- __SFHasCompletedBookmarkFeatureTextBackfillKey
- ___swift_closure_destructor.100Tm
- ___swift_closure_destructor.121Tm
- ___swift_closure_destructor.335Tm
- ___swift_closure_destructor.341Tm
- ___swift_closure_destructor.400Tm
- ___swift_closure_destructor.403Tm
- ___swift_closure_destructor.53Tm
- ___unnamed_61
- _swift_willThrowTypedImpl
CStrings:
+ "BookmarkFeatureTextBackfillCompletedForAltDSID"
+ "Failed to extract context for UUID %{public}s: %s"
+ "HideNotifyMeWhenReportAConcern"
+ "Looks Good"
+ "MobileSafari/SymbolView.ImageView.swift"
+ "availabilityIndicator="
+ "disablesTrailingCornerButtonTouchInsets"
+ "radar"
+ "selectedIndicator="
+ "sirittsd"
+ "v40@?0@\"SFUnifiedTabBarSection\"8{_NSRange=QQ}16^B32"
- "HasCompletedBookmarkFeatureTextBackfill"
- "TranslationButton"
- "ladybug"
```

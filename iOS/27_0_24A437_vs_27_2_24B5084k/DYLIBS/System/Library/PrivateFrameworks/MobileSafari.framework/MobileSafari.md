## MobileSafari

> `/System/Library/PrivateFrameworks/MobileSafari.framework/MobileSafari`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4fc1b0` | `0x4fff5c` | **`+0x3dac`** |
| `__AUTH_CONST.__const` | `0x21358` | `0x22780` | **`+0x1428`** |
| `__TEXT.__swift5_capture` | `0x7394` | `0x7b44` | **`+0x7b0`** |
| `__TEXT.__gcc_except_tab` | `0x77dc` | `0x7844` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x3b618` | `0x3b5c8` | **`-0x50`** |
| `__DATA.__data` | `0xe518` | `0xe558` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1cd50` | `0x1cd18` | **`-0x38`** |
| `__AUTH.__data` | `0x8018` | `0x8038` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0xab80` | `0xaba0` | **`+0x20`** |
| `__TEXT.__const` | `0x1cf34` | `0x1cf54` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x10498` | `0x10480` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x126d0` | `0x126b8` | **`-0x18`** |
| `__TEXT.__constg_swiftt` | `0x1201c` | `0x1202c` | **`+0x10`** |
| `__TEXT.__cstring` | `0x13979` | `0x13989` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xd3e6` | `0xd3f2` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x3a98` | `0x3aa0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1ce0` | `0x1cd8` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x6648` | `0x6650` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2af0` | `0x2af8` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x9654` | `0x965c` | **`+0x8`** |

### Other Changes

```diff

-625.1.29.10.29
+625.2.4.1.0

-  Functions: 27080
-  Symbols:   20319
+  Functions: 27220
+  Symbols:   20318
Symbols:
+ -[SFUnifiedBar didMoveToWindow]
+ -[SFUnifiedBarMetrics scalesSizeForContentSizeCategory]
+ -[SFUnifiedBarMetrics traitCollection]
+ -[SFUnifiedBarMetrics updateWithTraitCollection:inWindow:]
+ -[SFUnifiedTabBar didMoveToWindow]
+ GCC_except_table100
+ GCC_except_table178
+ GCC_except_table202
+ GCC_except_table206
+ GCC_except_table210
+ GCC_except_table222
+ _OBJC_CLASS_$_WBSUsageRetentionDonationManager
+ _OBJC_IVAR_$_SFUnifiedBarMetrics._scalesSizeForContentSizeCategory
+ __SFLocalTabGroupUUIDsBySceneIDDefaultsKey
+ ___swift_closure_destructor.211Tm
+ ___swift_closure_destructor.23Tm
+ ___swift_closure_destructor.240Tm
+ ___swift_closure_destructor.274Tm
+ ___swift_closure_destructor.287Tm
+ ___swift_closure_destructor.310Tm
+ ___swift_closure_destructor.314Tm
+ ___swift_closure_destructor.321Tm
+ ___swift_closure_destructor.354Tm
+ ___swift_closure_destructor.36Tm
+ ___swift_closure_destructor.388Tm
+ ___swift_closure_destructor.423Tm
+ ___swift_closure_destructor.457Tm
+ ___swift_closure_destructor.82Tm
+ ___swift_closure_destructor.99Tm
+ _associated conformance 12MobileSafari13HistoryEntityV10AppIntents08SyncableD0AaD0eD0
+ _associated conformance 12MobileSafari14BookmarkEntityV10AppIntents08SyncableD0AaD0eD0
+ _associated conformance 12MobileSafari21ReadingListItemEntityV10AppIntents08SyncableF0AaD0gF0
+ _objc_release_x11
- -[SFCapsuleView backgroundHeight]
- -[SFCapsuleView safeAreaInsetsDidChange]
- -[SFCapsuleView setBackgroundHeight:]
- -[SFUnifiedBarMetrics _updateWithContentSizeCategory:legibilityWeight:]
- -[SFUnifiedBarMetrics updateWithTraitCollection:]
- -[SFUnifiedTabBar itemsUseContentSafeAreaLayoutMargins]
- -[SFUnifiedTabBar setItemsUseContentSafeAreaLayoutMargins:]
- -[SFUnifiedTabBarItemView setUsesContentSafeAreaLayoutMargins:]
- -[SFUnifiedTabBarItemView usesContentSafeAreaLayoutMargins]
- GCC_except_table179
- GCC_except_table203
- GCC_except_table207
- GCC_except_table211
- GCC_except_table223
- _OBJC_IVAR_$_SFCapsuleView._backgroundHeight
- _OBJC_IVAR_$_SFUnifiedTabBar._itemsUseContentSafeAreaLayoutMargins
- _OBJC_IVAR_$_SFUnifiedTabBarItemView._usesContentSafeAreaLayoutMargins
- ___swift_closure_destructor.15Tm
- ___swift_closure_destructor.220Tm
- ___swift_closure_destructor.249Tm
- ___swift_closure_destructor.270Tm
- ___swift_closure_destructor.283Tm
- ___swift_closure_destructor.306Tm
- ___swift_closure_destructor.317Tm
- ___swift_closure_destructor.33Tm
- ___swift_closure_destructor.350Tm
- ___swift_closure_destructor.384Tm
- ___swift_closure_destructor.411Tm
- ___swift_closure_destructor.41Tm
- ___swift_closure_destructor.445Tm
- ___swift_closure_destructor.79Tm
- _associated conformance 12MobileSafari13HistoryEntityV10AppIntents09_SyncableD0AaD0eD0
- _associated conformance 12MobileSafari14BookmarkEntityV10AppIntents09_SyncableD0AaD0eD0
- _associated conformance 12MobileSafari21ReadingListItemEntityV10AppIntents09_SyncableF0AaD0gF0
CStrings:
+ "27_2"
+ "LocalTabGroupUUIDsBySceneID"
+ "MobileSafari/SFUIEdgeInsetsExtras.swift"
- "27_0"
- "Report a Concern"
- "exclamationmark.triangle"
```

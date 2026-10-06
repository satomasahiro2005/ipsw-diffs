## SpringBoardHome

> `/System/Library/PrivateFrameworks/SpringBoardHome.framework/SpringBoardHome`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x389278` | `0x38a1c4` | **`+0xf4c`** |
| `__TEXT.__objc_methlist` | `0x3eab4` | `0x3eb3c` | **`+0x88`** |
| `__AUTH_CONST.__cfstring` | `0x16da0` | `0x16e20` | **`+0x80`** |
| `__TEXT.__cstring` | `0x18a83` | `0x18af3` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0x74a8` | `0x7500` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0xf7e0` | `0xf820` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cae8` | `0x1cb18` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x9ea8` | `0x9ed0` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x4328` | `0x4350` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x1564` | `0x1588` | **`+0x24`** |
| `__DATA.__data` | `0x9648` | `0x9628` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1d68` | `0x1d80` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x58cd0` | `0x58cb8` | **`-0x18`** |
| `__DATA.__bss` | `0x3838` | `0x3828` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x3dc0` | `0x3dbc` | **`-0x4`** |

### Other Changes

```diff

-220.105.0.0.0
+223.100.0.0.0

-  Functions: 24643
-  Symbols:   33627
-  CStrings:  4565
+  Functions: 24663
+  Symbols:   33641
+  CStrings:  4569
Symbols:
+ +[SBIconView _allowsPLKCachePrewarmingForBundleIdentifier:]
+ +[SBIconView allowPLKCachePrewarming]
+ -[SBFolderIcon folder:didMoveIcon:]
+ -[SBHAddWidgetSheetViewController searchBar:shouldChangeTextInRange:replacementText:]
+ -[SBHIconManager _extraIconImageCacheConfigurationsByLimitingUniqueTintedConfigurations:]
+ -[SBHIconManager canSwapApplicationIconsInProminentPositionsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:]
+ -[SBHIconManager canSwapApplicationIconsInProminentPositionsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:focusModeIdentifier:]
+ -[SBHIconManager replaceApplicationIconsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:]
+ -[SBHIconManager swapApplicationIconsInProminentPositionsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:]
+ -[SBHIconManager swapApplicationIconsInProminentPositionsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:focusModeIdentifier:]
+ -[SBHIconManager swapApplicationIconsInProminentPositionsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:inRootFolder:focusModeIdentifier:]
+ -[SBIconDragManager createNewFolderFromRecipientIcon:additionalIcons:inListModel:]
+ -[SBIconListModel listContainingIcon:]
+ -[SBIconListModel listContainingIconWithIdentifier:]
+ -[SBIconListModel rotatedGridCellInfo]
+ GCC_except_table1117
+ GCC_except_table1118
+ GCC_except_table1120
+ GCC_except_table1136
+ GCC_except_table1143
+ GCC_except_table118
+ GCC_except_table121
+ GCC_except_table138
+ GCC_except_table148
+ GCC_except_table160
+ GCC_except_table197
+ GCC_except_table202
+ GCC_except_table217
+ GCC_except_table250
+ GCC_except_table253
+ GCC_except_table256
+ GCC_except_table261
+ GCC_except_table281
+ GCC_except_table292
+ GCC_except_table330
+ GCC_except_table332
+ GCC_except_table338
+ GCC_except_table344
+ GCC_except_table363
+ GCC_except_table371
+ GCC_except_table372
+ GCC_except_table391
+ GCC_except_table439
+ GCC_except_table488
+ GCC_except_table497
+ GCC_except_table503
+ GCC_except_table534
+ GCC_except_table545
+ GCC_except_table568
+ GCC_except_table570
+ GCC_except_table606
+ GCC_except_table636
+ GCC_except_table660
+ GCC_except_table663
+ GCC_except_table704
+ GCC_except_table71
+ _CGColorCreateCopyWithAlpha
+ _CGColorGetAlpha
+ _SBHPerformanceFlagEnabled.flagState
+ ___153-[SBHIconManager swapApplicationIconsInProminentPositionsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:inRootFolder:focusModeIdentifier:]_block_invoke
+ ___153-[SBHIconManager swapApplicationIconsInProminentPositionsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:inRootFolder:focusModeIdentifier:]_block_invoke_2
+ ___38-[SBIconListModel listContainingIcon:]_block_invoke
+ ___39-[SBFolderIconImageView layoutSubviews]_block_invoke
+ ___52-[SBIconListModel listContainingIconWithIdentifier:]_block_invoke
+ ___82-[SBIconDragManager createNewFolderFromRecipientIcon:additionalIcons:inListModel:]_block_invoke
+ ___82-[SBIconDragManager createNewFolderFromRecipientIcon:additionalIcons:inListModel:]_block_invoke_2
+ ___block_descriptor_136_e33_v32?0"SBHIconLayerView"8Q16^B24l
+ ___block_descriptor_56_e8_32s40s48s_e36_v32?0"SBIcon"8"NSIndexPath"16^B24ls32l8s40l8s48l8
- -[SBHIconManager purgeUnnecessaryAppearanceIconImageData]
- -[SBHIconManager swapApplicationIconsInProminentPositionsWithBundleIdentifier:withApplicationIconsWithWithBundleIdentifier:inRootFolder:focusModeIdentifier:]
- -[SBHLibraryCategoryStackView displayedIconImageInfo]
- -[SBHLibraryCategoryStackView setDisplayedIconImageInfo:]
- -[SBIconDragManager addIcons:intoFolderIcon:openFolderOnFinish:]
- -[SBIconDragManager createNewFolderFromRecipientIcon:grabbedIcon:inListModel:]
- GCC_except_table1112
- GCC_except_table1113
- GCC_except_table1115
- GCC_except_table1131
- GCC_except_table1138
- GCC_except_table149
- GCC_except_table156
- GCC_except_table198
- GCC_except_table209
- GCC_except_table213
- GCC_except_table246
- GCC_except_table248
- GCC_except_table257
- GCC_except_table277
- GCC_except_table293
- GCC_except_table327
- GCC_except_table328
- GCC_except_table334
- GCC_except_table340
- GCC_except_table342
- GCC_except_table360
- GCC_except_table368
- GCC_except_table369
- GCC_except_table389
- GCC_except_table435
- GCC_except_table484
- GCC_except_table489
- GCC_except_table496
- GCC_except_table499
- GCC_except_table530
- GCC_except_table541
- GCC_except_table564
- GCC_except_table566
- GCC_except_table604
- GCC_except_table631
- GCC_except_table655
- GCC_except_table661
- GCC_except_table702
- GCC_except_table99
- _OBJC_IVAR_$_SBHLibraryCategoryStackView._displayedIconImageInfo
- _SBHFeatureEnabled.__verboseCachingLoggingEnabled
- _SBHFeatureEnabled.onceToken
- ___157-[SBHIconManager swapApplicationIconsInProminentPositionsWithBundleIdentifier:withApplicationIconsWithWithBundleIdentifier:inRootFolder:focusModeIdentifier:]_block_invoke
- ___157-[SBHIconManager swapApplicationIconsInProminentPositionsWithBundleIdentifier:withApplicationIconsWithWithBundleIdentifier:inRootFolder:focusModeIdentifier:]_block_invoke_2
- ___78-[SBIconDragManager createNewFolderFromRecipientIcon:grabbedIcon:inListModel:]_block_invoke
- ___78-[SBIconDragManager createNewFolderFromRecipientIcon:grabbedIcon:inListModel:]_block_invoke_2
- ___SBHFeatureEnabled_block_invoke
- ___block_descriptor_88_e33_v32?0"SBHIconLayerView"8Q16^B24l
CStrings:
+ "filters.tintSaturation.inputAmount"
+ "icon view class opts out of PLK cache prewarming"
+ "moved icon"
+ "springboard"
+ "tintSaturation"
- "VerboseCachingLogging"
```

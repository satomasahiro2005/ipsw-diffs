## AccessorySetupKit

> `/System/Library/Frameworks/AccessorySetupKit.framework/AccessorySetupKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22544` | `0x24958` | **`+0x2414`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x9f8` | **`+0x9f8`** |
| `__AUTH.__objc_data` | `0xad0` | `0x188` | **`-0x948`** |
| `__TEXT.__cstring` | `0x3ab1` | `0x3c01` | **`+0x150`** |
| `__TEXT.__eh_frame` | `0x78` | `0x198` | **`+0x120`** |
| `__AUTH_CONST.__objc_const` | `0x2de0` | `0x2eb8` | **`+0xd8`** |
| `__AUTH_CONST.__cfstring` | `0x1620` | `0x16e0` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x28b` | `0x32b` | **`+0xa0`** |
| `__DATA_DIRTY.__data` | `—` | `0x90` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x7b8` | `0x848` | **`+0x90`** |
| `__AUTH_CONST.__auth_got` | `0x810` | `0x898` | **`+0x88`** |
| `__TEXT.__const` | `0x5d2` | `0x658` | **`+0x86`** |
| `__TEXT.__objc_methlist` | `0x20f0` | `0x2168` | **`+0x78`** |
| `__AUTH.__data` | `0x90` | `0x30` | **`-0x60`** |
| `__AUTH_CONST.__const` | `0x470` | `0x4c0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x19e0` | `0x1a28` | **`+0x48`** |
| `__DATA.__data` | `0x990` | `0x9c0` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x2dc` | `0x308` | **`+0x2c`** |
| `__TEXT.__swift5_capture` | `0xc0` | `0xec` | **`+0x2c`** |
| `__TEXT.__swift5_typeref` | `0x2ca` | `0x2f6` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x758` | `0x780` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x4d0` | `0x4f8` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x4d0` | `0x4e4` | **`+0x14`** |
| `__AUTH_CONST.__objc_doubleobj` | `—` | `0x10` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1cc` | `0x1dc` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xe8` | `0xf8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xc0` | `0xc8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x18` | `0x1c` | **`+0x4`** |

### Other Changes

```diff

-2700.27.0.0.0
+2700.30.0.0.0

+  - /System/Library/Frameworks/MarketplaceKit.framework/MarketplaceKit

-  Functions: 821
-  Symbols:   1416
-  CStrings:  421
+  Functions: 853
+  Symbols:   1451
+  CStrings:  434
Symbols:
+ +[ASAccessoryInfoViewController companionSpecifiersFromList:insertIndex:]
+ -[ASAccessoryCompanionAppInfo distributorBundleID]
+ -[ASAccessoryCompanionAppInfo distributorName]
+ -[ASAccessoryCompanionAppInfo initWithBundleID:name:publisherName:adamID:icon:appIsInstalled:distributorBundleID:distributorName:]
+ -[ASAccessoryCompanionAppView initWithBundleID:appInfo:]
+ -[ASAccessoryInfoViewController buildSpecifiers]
+ -[ASAccessoryInfoViewController resolveCompanionAppIfNeeded:]
+ -[ASAccessoryInfoViewController revealCompanionSectionAnimated]
+ -[ASAccessoryInfoViewController viewCompanionAppInBrowser:]
+ GCC_except_table1
+ GCC_except_table10
+ GCC_except_table12
+ GCC_except_table65
+ GCC_except_table70
+ _OBJC_CLASS_$_NSConstantDoubleNumber
+ _OBJC_CLASS_$__TtC17AccessorySetupKit25ASAccessoryAltMarketplace
+ _OBJC_IVAR_$_ASAccessoryCompanionAppInfo._distributorBundleID
+ _OBJC_IVAR_$_ASAccessoryCompanionAppInfo._distributorName
+ _OBJC_IVAR_$_ASAccessoryInfoViewController._companionResolution
+ _OBJC_IVAR_$_ASAccessoryInfoViewController._companionResolutionStarted
+ _OBJC_IVAR_$_ASAccessoryInfoViewController._resolvedCompanionAppInfo
+ _OBJC_METACLASS_$__TtC17AccessorySetupKit25ASAccessoryAltMarketplace
+ _PSTableCellHeightKey
+ __CLASS_METHODS__TtC17AccessorySetupKit25ASAccessoryAltMarketplace
+ __DATA__TtC17AccessorySetupKit25ASAccessoryAltMarketplace
+ __INSTANCE_METHODS__TtC17AccessorySetupKit25ASAccessoryAltMarketplace
+ __METACLASS_DATA__TtC17AccessorySetupKit25ASAccessoryAltMarketplace
+ __OBJC_$_CLASS_METHODS_ASAccessoryInfoViewController
+ ___56-[ASAccessoryCompanionAppView initWithBundleID:appInfo:]_block_invoke
+ ___56-[ASAccessoryCompanionAppView initWithBundleID:appInfo:]_block_invoke_2
+ ___61-[ASAccessoryInfoViewController resolveCompanionAppIfNeeded:]_block_invoke
+ ___61-[ASAccessoryInfoViewController resolveCompanionAppIfNeeded:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40w_e49_v24?0"ASAccessoryCompanionAppInfo"8"NSError"16lw40l8s32l8
+ ___block_descriptor_56_e8_32s40s48w_e5_v8?0lw48l8s32l8s40l8
+ ___swift_async_cont_functlets
+ ___swift_async_entry_functlets
+ ___swift_async_ret_functlets
+ _swift_getErrorValue
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
+ _symbolic SS
+ _symbolic ScA_pSg
+ _symbolic ScPSg
+ _symbolic _____ 17AccessorySetupKit25ASAccessoryAltMarketplaceC
+ _symbolic _____XMT 17AccessorySetupKit25ASAccessoryAltMarketplaceC
+ _symbolic ytIeAgHr_
- -[ASAccessoryCompanionAppInfo initWithBundleID:name:publisherName:adamID:icon:appIsInstalled:]
- -[ASAccessoryCompanionAppView loadingCompletionHandler]
- -[ASAccessoryCompanionAppView setLoadingCompletionHandler:]
- -[ASAccessoryInfoViewController tableView:heightForRowAtIndexPath:]
- GCC_except_table0
- GCC_except_table64
- GCC_except_table9
- _OBJC_IVAR_$_ASAccessoryCompanionAppView._loadingCompletionHandler
- ___48-[ASAccessoryCompanionAppView initWithBundleID:]_block_invoke
- ___48-[ASAccessoryCompanionAppView initWithBundleID:]_block_invoke_2
- ___65-[ASAccessoryInfoViewController tableView:cellForRowAtIndexPath:]_block_invoke_2
- ___65-[ASAccessoryInfoViewController tableView:cellForRowAtIndexPath:]_block_invoke_3
- ___block_descriptor_56_e8_32s40w48w_e5_v8?0lw40l8w48l8s32l8
CStrings:
+ "-[ASAccessoryInfoViewController viewCompanionAppInBrowser:]"
+ "ASAccessoryCompanionAppResolved"
+ "AccessorySetupKit/ASAccessoryAltMarketplace.swift"
+ "Companion app browser fallback: invalid manufacturer URL: %@"
+ "Failed to convert adamID to UInt64: %s"
+ "Failed to open alt marketplace product page: %s"
+ "Opening alt marketplace product page: distributor=%s, adamID=%s"
+ "View in Browser"
+ "com.apple.AccessorySetupKit"
+ "com.apple.AppStore"
+ "companionApp"
+ "companionAppBrowser_"
+ "companionAppInfo"
```

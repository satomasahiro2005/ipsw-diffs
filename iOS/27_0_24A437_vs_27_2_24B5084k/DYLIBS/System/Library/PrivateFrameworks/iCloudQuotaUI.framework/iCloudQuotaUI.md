## iCloudQuotaUI

> `/System/Library/PrivateFrameworks/iCloudQuotaUI.framework/iCloudQuotaUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x166be0` | `0x1670a8` | **`+0x4c8`** |
| `__AUTH_CONST.__objc_const` | `0x21f70` | `0x22090` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0xba92` | `0xbba2` | **`+0x110`** |
| `__TEXT.__objc_methlist` | `0x9d94` | `0x9e64` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x7f20` | `0x7fe0` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x6b40` | `0x6bc8` | **`+0x88`** |
| `__AUTH.__objc_data` | `0x39e8` | `0x3a38` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0xeb8` | `0xe7c` | **`-0x3c`** |
| `__TEXT.__cstring` | `0xae26` | `0xae56` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2718` | `0x2738` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2358` | `0x2368` | **`+0x10`** |
| `__TEXT.__const` | `0xac34` | `0xac24` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x5450` | `0x5460` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xbd8` | `0xbe4` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x1d18` | `0x1d20` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x588` | `0x590` | **`+0x8`** |

### Other Changes

```diff

-301.24.0.27.0
+301.24.1.3.0

-  Functions: 8036
-  Symbols:   8187
-  CStrings:  2567
+  Functions: 8052
+  Symbols:   8219
+  CStrings:  2575
Symbols:
+ +[ICQUIOrientation supportedOrientations:isEnhancedLandscapeEnabled:]
+ +[ICQUIOrientation supportedOrientations]
+ -[ICQInAppAction actionIdentifier]
+ -[ICQInAppAction setActionIdentifier:]
+ -[ICQInAppAlert initWithOffer:alertKey:pendingItemsCount:]
+ -[ICQInAppMessaging _actionsForBannerSpecification:offer:pendingItemsCount:]
+ -[ICQInAppMessaging _fetchSharedAlbumMessageForReason:placement:pendingItemsCount:completion:]
+ -[ICQInAppMessaging fetchAlertForReason:placement:completion:]
+ -[ICQInAppMessaging fetchMessageForReason:placement:pendingItemsCount:withCompletion:]
+ -[ICQInAppMessaging fetchMessageWithPlacement:pendingItemsCount:completion:]
+ -[ICQInAppMessaging mockOffer]
+ -[ICQInAppMessaging setMockOffer:]
+ -[ICQInAppMessaging sharedAlbumMessageForOffer:placement:pendingItemsCount:]
+ -[ICQLinkInAppAction addAlertFromLink:offer:pendingItemsCount:]
+ -[ICQLinkInAppAction initWithLink:inOffer:pendingItemsCount:]
+ -[ICQLinkInAppAction pendingItemsCount]
+ -[ICQLinkInAppAction setPendingItemsCount:]
+ GCC_except_table26
+ GCC_except_table44
+ GCC_except_table54
+ GCC_except_table58
+ GCC_except_table66
+ _ICQInAppActionIdentifierCancel
+ _ICQInAppActionIdentifierMoveToOnMyDevice
+ _ICQUIInAppMessageReasonRecoveryFailed
+ _ICQUIMessagePlacementInAppAlert
+ _OBJC_CLASS_$_ICQUIOrientation
+ _OBJC_IVAR_$_ICQInAppAction._actionIdentifier
+ _OBJC_IVAR_$_ICQInAppMessaging._mockOffer
+ _OBJC_IVAR_$_ICQLinkInAppAction._pendingItemsCount
+ _OBJC_METACLASS_$_ICQUIOrientation
+ __OBJC_$_CLASS_METHODS_ICQUIOrientation
+ __OBJC_CLASS_RO_$_ICQUIOrientation
+ __OBJC_METACLASS_RO_$_ICQUIOrientation
+ __UIEnhancedLandscapeEnabled
+ ___68-[ICQInAppMessaging observeValueForKeyPath:ofObject:change:context:]_block_invoke
+ ___94-[ICQInAppMessaging _fetchSharedAlbumMessageForReason:placement:pendingItemsCount:completion:]_block_invoke
+ _os_variant_has_internal_diagnostics
- -[ICQLinkInAppAction addAlertFromLink:offer:]
- GCC_except_table49
- GCC_except_table59
- GCC_except_table60
- ___60-[ICQInternetPrivacyDetailSpecifierProvider _switchOffAlert]_block_invoke_3
- ___76-[ICQInAppMessaging _fetchSharedAlbumMessageForReason:placement:completion:]_block_invoke
CStrings:
+ "InAppAlert"
+ "RecoveryFailed"
+ "Shared Collections: fetchMessageForReason:placement:pendingItemsCount: called with reason: %@, placement: %@, count: %@"
+ "cancelBtnId"
+ "debug-mock-offer"
+ "fetchAlertForReason:%{public}@ placement:%{public}@ not yet implemented, returning unavailable error."
+ "fetchMessageForReason:placement: called with reason: %@, placement: %@"
+ "fetchMessageWithPlacement called with placement: %@"
+ "fetchMessageWithPlacement:pendingItemsCount: called with placement: %@, count: %@"
+ "moveToOnMyDeviceBtnId"
+ "pendingItemsCount"
- "INTERNET_PRIVACY_OPEN_SYSTEM_STATUS_BUTTON_TITLE"
- "Shared Collections: fetchMessageForReason:placement: called with reason: %@, placement: %@"
- "Shared Collections: fetchMessageWithPlacement called with placement: %@"
```

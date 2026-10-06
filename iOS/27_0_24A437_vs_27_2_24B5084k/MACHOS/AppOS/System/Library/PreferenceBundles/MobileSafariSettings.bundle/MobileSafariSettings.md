## MobileSafariSettings

> `/System/Library/PreferenceBundles/MobileSafariSettings.bundle/MobileSafariSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x11f5e` | `0x11f7e` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xd060` | `0xd040` | **`-0x20`** |
| `__TEXT.__text` | `0x6d564` | `0x6d558` | **`-0xc`** |
| `__DATA.__objc_const` | `0x7ad8` | `0x7ae0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x4644` | `0x464c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.1.29.10.29
+7625.2.4.1.0

-  Symbols:   5577
+  Symbols:   5576
Symbols:
+ _OBJC_CLASS_$_WBSUsageRetentionDonationManager
+ _objc_msgSend$clearDonatedEventsSinceDate:
- _OBJC_CLASS_$_WBSTrialManager
- _objc_msgSend$isAllowFavoritesInFrequentlyVisitedEnabled
- _objc_msgSend$shared
Functions:
~ -[FrequentlyVisitedSitesController _canonicalizedFavoritesURLStringSet] : 416 -> 372
~ -[SafariSettingsController _safariClearHistoryAndDataAddedAfterDate:beforeDate:profileIdentifier:clearAllProfiles:closeTabs:] : 2896 -> 2928
CStrings:
+ "clearDonatedEventsSinceDate:"
+ "profileConnectionDidReceiveAllowCloudSyncChangedNotification:userInfo:"
- "isAllowFavoritesInFrequentlyVisitedEnabled"
- "shared"
```

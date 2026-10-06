## NotificationsSettings

> `/System/Library/PreferenceBundles/NotificationsSettings.bundle/NotificationsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5e358` | `0x5eed8` | **`+0xb80`** |
| `__TEXT.__objc_methname` | `0x84df` | `0x860f` | **`+0x130`** |
| `__TEXT.__cstring` | `0x3dcb` | `0x3edb` | **`+0x110`** |
| `__TEXT.__objc_stubs` | `0x6300` | `0x63e0` | **`+0xe0`** |
| `__DATA_CONST.__cfstring` | `0x3300` | `0x3380` | **`+0x80`** |
| `__DATA.__objc_const` | `0x5ee0` | `0x5f40` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x1f80` | `0x1fc8` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x258c` | `0x25c4` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x1e90` | `0x1ec0` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x1548` | `0x1570` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x9b0` | `0x9d0` | **`+0x20`** |
| `__DATA.__data` | `0x12a8` | `0x12c0` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0xf58` | `0xf70` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x1e78` | `0x1e60` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x1688` | `0x16a0` | **`+0x18`** |
| `__DATA.__bss` | `0x2228` | `0x2238` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1a0` | `0x1ac` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-310.2.2.0.0
+310.2.4.0.0

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 1862
-  Symbols:   560
-  CStrings:  2011
+  Functions: 1870
+  Symbols:   568
+  CStrings:  2029
Symbols:
+ _NCBundleIdentifiersExcludedFromSiri
+ _NCDevicePrefixedImageForKeyWithDefaultSystemClock
+ _NCIsExcludedFromSiriForBundleIdentifier
+ _OBJC_CLASS_$_UITraitDisplayScale
+ _OBJC_CLASS_$_UITraitUserInterfaceStyle
+ _TCCAccessCopyBundleIdentifiersDisabledForService
+ _UIGraphicsEndImageContext
+ _UIRectCenteredXInRectScale
+ _UIRoundToScale
+ _kNCSiriAppExclusionChangedBundleIdentifiersKey
+ _kNCSiriAppExclusionChangedNotification
+ _kTCCServiceSiriAccess
- _MGIsDeviceOfType
- _NCDeviceImageWithDefaultSystemClock
- _NCLoadFromCoverSheetKit
- _NCLockScreenTimeAttributedStringWithFont
CStrings:
+ "@\"NSSet\""
+ "AppExclusions"
+ "EXCLUDED_FROM_SIRI_BUNDLE_IDENTIFIERS_KEY"
+ "EXCLUDED_FROM_SIRI_KEY"
+ "IntelligenceFlow"
+ "NCSiriAppExclusionChangedBundleIdentifiers"
+ "NCSiriAppExclusionChangedNotification"
+ "RESTRICT_ACCESS_ID"
+ "SPOKEN_NOTIFICATIONS_APP_EXCLUDED_FROM_SIRI_EDIT_LINK"
+ "SPOKEN_NOTIFICATIONS_APP_EXCLUDED_FROM_SIRI_FOOTER"
+ "SiriSettings"
+ "_builtExcludedFromSiriBundleIdentifiers"
+ "_didPushExcludedAppsSettings"
+ "_excludedFromSiri"
+ "_excludedFromSiriBundleIdentifiers"
+ "_updateForTraitChange"
+ "ipad-legacy"
+ "ipad-legacy-banners"
+ "ipad-legacy-count"
+ "ipad-legacy-history"
+ "ipad-legacy-list"
+ "ipad-legacy-lockscreen"
+ "ipad-legacy-stack"
+ "iphone-D20"
+ "iphone-D5x"
+ "iphone-D6x"
+ "iphone-D7x"
+ "iphone-V68"
+ "iphone-V68-banners"
+ "iphone-V68-count"
+ "iphone-V68-history"
+ "iphone-V68-lockscreen"
+ "iphone-V68-stack"
+ "iphone-V6x"
+ "isEqualToSet:"
+ "postNotificationName:object:userInfo:"
+ "registerForTraitChanges:withTarget:action:"
+ "set"
+ "setWithArray:"
+ "settingsNavigationProxy_pushPaneWithContentIdentifier:bundleName:"
+ "siriAppExclusionChanged:"
+ "tappedExcludedAppsSettings:"
+ "userInfo"
- "%@-dark"
- "%@-legacy"
- "-legacy"
- "D20"
- "D5x"
- "D6x"
- "D7x"
- "V68"
- "V6x"
- "com.apple.CoverSheetKit"
- "ipad-banners-dark"
- "ipad-banners-legacy"
- "ipad-banners-legacy-dark"
- "ipad-count-legacy"
- "ipad-history-dark"
- "ipad-history-legacy"
- "ipad-history-legacy-dark"
- "ipad-list-legacy"
- "ipad-lockscreen-dark"
- "ipad-lockscreen-legacy"
- "ipad-lockscreen-legacy-dark"
- "ipad-stack-legacy"
- "iphone"
- "traitCollectionDidChange:"
- "updateForUserInterfaceStyleChange"
```

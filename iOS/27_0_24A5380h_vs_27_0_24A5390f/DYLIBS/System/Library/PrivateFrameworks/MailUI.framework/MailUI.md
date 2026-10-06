## MailUI

> `/System/Library/PrivateFrameworks/MailUI.framework/MailUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x351150` | `0x3509cc` | **`-0x784`** |
| `__TEXT.__cstring` | `0xe6d9` | `0xe469` | **`-0x270`** |
| `__AUTH_CONST.__const` | `0x12838` | `0x12888` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x9d94` | `0x9db4` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x7640` | `0x7620` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x5684` | `0x56a4` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x18f86` | `0x18f9a` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x3168` | `0x3158` | **`-0x10`** |
| `__DATA.__data` | `0x7118` | `0x7128` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x2fc8` | `0x2fd8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1f78` | `0x1f88` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x6588` | `0x6598` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x35f0` | `0x35e0` | **`-0x10`** |
| `__TEXT.__const` | `0x11304` | `0x11314` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x6be0` | `0x6be8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x180` | `0x184` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x14c` | `0x150` | **`+0x4`** |

### Other Changes

```diff

-3895.100.17.2.1
+3897.100.8.2.5

-  - /System/Library/Frameworks/ColorSync.framework/ColorSync

-  - /usr/lib/libMobileGestalt.dylib

-  Functions: 15519
-  Symbols:   8711
-  CStrings:  2068
+  Functions: 15527
+  Symbols:   8714
+  CStrings:  2061
Symbols:
+ +[CSSuggestion(MailUI) mui_personSuggestionForEmailAddresses:displayName:alternateDisplayNames:contactIdentifier:contactScope:userTypedText:currentSuggestion:]
+ +[UINavigationBar(DCI) mf_shouldUseDesktopClassNavigationBarForTraitCollection:windowScene:]
+ -[UIWindowScene(MailUI) mui_isWide]
+ _CGColorSpaceCreateWithName
+ _MDItemContactIdentifier
+ __UIEnhancedLandscapeEnabled
+ ___swift_allocate_boxed_opaque_existential_0
+ _kCGColorSpaceSRGB
+ _symbolic ypIegn_
+ _symbolic ypytIegnr_
- +[CSSuggestion(MailUI) mui_personSuggestionForEmailAddresses:displayName:alternateDisplayNames:contactScope:userTypedText:currentSuggestion:]
- _CGColorSpaceCreateWithICCData
- _ColorSyncProfileCopyData
- _ColorSyncProfileCreateWithName
- _MobileGestalt_get_current_device
- _MobileGestalt_get_wapiCapability
- _kColorSyncSRGBProfile
CStrings:
+ " may not be available while Mail is indexing."
+ "New-search-available explanation. Placeholder is a time window like '6 months'."
+ "Search-indexing explanation shown while the index is still being prepared."
+ "Some search results may not be available while Mail is indexing. This may take more than a few days."
+ "Some search results older than "
- " is locked, charging, and connected to WLAN. Some results older than "
- " is locked, charging, and connected to WLAN. This may take more than a few days."
- " is locked, charging, and connected to Wi-Fi. Some results older than "
- " is locked, charging, and connected to Wi-Fi. This may take more than a few days."
- " may not appear until complete."
- "Mail downloads and organizes messages for better results when "
- "MailUI/EMSearchIndexScenario+Strings.swift"
- "New-search-available explanation, WLAN variant. First placeholder is the device noun (e.g. iPhone), second is a time window like '6 months'."
- "New-search-available explanation, Wi-Fi variant. First placeholder is the device noun (e.g. iPhone), second is a time window like '6 months'."
- "Search-indexing explanation, WLAN variant. Placeholder is the device noun (e.g. iPhone, iPad)."
- "Search-indexing explanation, Wi-Fi variant. Placeholder is the device noun (e.g. iPhone, iPad)."
- "failed to create sRGB profile"
```

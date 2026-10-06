## SettingsHost

> `/System/Library/PrivateFrameworks/SettingsHost.framework/SettingsHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f5d0` | `0x7a2c0` | **`-0x5310`** |
| `__TEXT.__oslogstring` | `0x2344` | `0x1f64` | **`-0x3e0`** |
| `__TEXT.__const` | `0x5298` | `0x4fa8` | **`-0x2f0`** |
| `__TEXT.__swift5_typeref` | `0x1820` | `0x16d2` | **`-0x14e`** |
| `__DATA.__data` | `0x870` | `0x738` | **`-0x138`** |
| `__TEXT.__constg_swiftt` | `0x1518` | `0x13e0` | **`-0x138`** |
| `__AUTH_CONST.__const` | `0x4510` | `0x4400` | **`-0x110`** |
| `__DATA.__bss` | `0x3ce0` | `0x3bd0` | **`-0x110`** |
| `__TEXT.__eh_frame` | `0x2238` | `0x2148` | **`-0xf0`** |
| `__TEXT.__unwind_info` | `0x1778` | `0x1690` | **`-0xe8`** |
| `__TEXT.__swift5_fieldmd` | `0x1624` | `0x1590` | **`-0x94`** |
| `__AUTH_CONST.__objc_const` | `0xc90` | `0xc08` | **`-0x88`** |
| `__AUTH_CONST.__auth_got` | `0xfa8` | `0xf48` | **`-0x60`** |
| `__TEXT.__cstring` | `0x3b58` | `0x3b08` | **`-0x50`** |
| `__TEXT.__swift5_reflstr` | `0x165e` | `0x160e` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x170` | `0x148` | **`-0x28`** |
| `__DATA.__common` | `0x60` | `0x48` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0x3c8` | `0x3b0` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x320` | `0x318` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x38` | `0x30` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x160` | `0x158` | **`-0x8`** |

### Other Changes

```diff

-27.0.20.100.0
+2027.0.2.0.0

-  - /System/Library/Frameworks/SwiftUI.framework/SwiftUI

-  Functions: 2114
-  Symbols:   849
-  CStrings:  588
+  Functions: 2036
+  Symbols:   833
+  CStrings:  562
Symbols:
- __IVARS__TtC12SettingsHost17NavigationHistory
- _associated conformance 12SettingsHost21NavigationHistoryItemVyxGs12IdentifiableAA2IDsAEP_SH
- _flat unique 12SettingsHost27NavigationDestinationLoader_px0D0AaBPRts_XP
- _generic environment 12SettingsHost21NavigationDestinationRzl
- _symbolic $s12SettingsHost21NavigationDestinationP
- _symbolic $s12SettingsHost27NavigationDestinationLoaderP
- _symbolic 11Destination_____Qyd__ 12SettingsHost27NavigationDestinationLoaderP
- _symbolic 11Destination_____Qz 12SettingsHost27NavigationDestinationLoaderP
- _symbolic Say_____yxGG 12SettingsHost21NavigationHistoryItemV
- _symbolic _____ 12SettingsHost17NavigationHistoryC
- _symbolic _____ 12SettingsHost21NavigationHistoryItemV
- _symbolic _____Sg 7SwiftUI5ImageV
- _symbolic _____xXjSg l12SettingsHost27NavigationDestinationLoader_px0D0Rts_XPXGMq
- _symbolic _____ySiG s16PartialRangeFromV
- _symbolic _____yxG 12SettingsHost17NavigationHistoryC
- _symbolic _____yxG 12SettingsHost21NavigationHistoryItemV
CStrings:
- "   Cleared forward history"
- "   Current state: index=%ld, count=%ld"
- "   Full history: %s"
- "   New state: index=%ld, count=%ld"
- "   Returning %ld items: %s"
- "   Returning EMPTY (at end or invalid index)"
- "   Returning EMPTY (currentIndex <= 0)"
- "   canGoBack=%{bool}d, canGoForward=%{bool}d"
- "  identifier: %s"
- "  subdestination: %s"
- "Cannot go back: already at beginning"
- "Cannot go forward: already at end"
- "Cannot load: no current item"
- "Cannot load: no loader configured"
- "Cannot navigate to item: not found in history"
- "Clearing history"
- "Going back to index %ld"
- "Going forward to index %ld"
- "Going to item at index %ld: %s"
- "Loader is nil"
- "Loading destination: %s"
- "Navigation History"
- "SettingsHost/NavigationHistory.swift"
- "📊 getBackwardHistory() called - currentIndex=%ld, history.count=%ld"
- "📊 getForwardHistory() called - currentIndex=%ld, history.count=%ld"
- "📝 append() called for: %s"
```

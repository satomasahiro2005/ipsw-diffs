## BackBoard

> `/System/Library/AccessibilityBundles/BackBoard.axbundle/BackBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27e4c` | `0x281ec` | **`+0x3a0`** |
| `__TEXT.__oslogstring` | `0x1e62` | `0x1fc0` | **`+0x15e`** |
| `__AUTH_CONST.__objc_const` | `0x3038` | `0x3098` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x22d4` | `0x232c` | **`+0x58`** |
| `__TEXT.__cstring` | `0x2317` | `0x2369` | **`+0x52`** |
| `__AUTH_CONST.__cfstring` | `0x1d60` | `0x1da0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1bd8` | `0x1c08` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0xfa0` | `0xfc0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xc58` | `0xc68` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x158` | `0x160` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd08` | `0xd10` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 1017
-  Symbols:   2092
-  CStrings:  486
+  Functions: 1027
+  Symbols:   2106
+  CStrings:  492
Symbols:
+ -[AXBAccessibilityManager _commonEventRepForTouchEventWithType:location:force:flags:contextId:displayId:]
+ -[AXBAccessibilityManager _sendFingerEvent:location:force:flags:contextId:displayId:]
+ -[AXBAccessibilityManager _sendStylusEvent:location:force:altitude:azimuth:flags:contextId:displayId:]
+ -[AXBLiveCaptionsManager .cxx_destruct]
+ -[AXBLiveCaptionsManager handleLanguagePreferencesChanged]
+ -[AXBLiveCaptionsManager handleSpringBoardFinishedStartup]
+ -[AXBLiveCaptionsManager lastKnownLanguage]
+ -[AXBLiveCaptionsManager setLastKnownLanguage:]
+ -[AXBLiveCaptionsManager setShouldRestoreLiveCaptionsAfterLanguageChange:]
+ -[AXBLiveCaptionsManager shouldRestoreLiveCaptionsAfterLanguageChange]
+ GCC_except_table479
+ GCC_except_table530
+ GCC_except_table576
+ GCC_except_table605
+ GCC_except_table622
+ GCC_except_table635
+ GCC_except_table647
+ GCC_except_table680
+ GCC_except_table718
+ GCC_except_table732
+ GCC_except_table806
+ _CFPreferencesCopyAppValue
+ _OBJC_IVAR_$_AXBLiveCaptionsManager._lastKnownLanguage
+ _OBJC_IVAR_$_AXBLiveCaptionsManager._shouldRestoreLiveCaptionsAfterLanguageChange
+ __AXSLiveTranscriptionSetEnabled
+ ___58-[AXBLiveCaptionsManager handleSpringBoardFinishedStartup]_block_invoke
+ __axbLiveCaptionsLanguagePreferencesChanged
+ __axbLiveCaptionsSpringBoardFinishedStartup
- -[AXBAccessibilityManager _commonEventRepForTouchEventWithType:location:force:flags:contextId:]
- -[AXBAccessibilityManager _sendFingerEvent:location:force:flags:contextId:]
- -[AXBAccessibilityManager _sendStylusEvent:location:force:altitude:azimuth:flags:contextId:]
- GCC_except_table471
- GCC_except_table520
- GCC_except_table566
- GCC_except_table595
- GCC_except_table612
- GCC_except_table625
- GCC_except_table637
- GCC_except_table670
- GCC_except_table708
- GCC_except_table722
- GCC_except_table796
CStrings:
+ "AppleLanguagePreferencesChangedNotification"
+ "Primary language changed while Live Captions enabled; disabling for the duration of the language change"
+ "Restoring Live Captions after language change"
+ "SpringBoard finished startup after language change; Live Captions not supported for new language, leaving disabled"
+ "SpringBoard finished startup after language change; restoring Live Captions in %.0fs"
+ "com.apple.springboard.finishedstartup"
```
